# ManniWatch
{{ template:badges }}
## Packages
| Package | NPM | Coverage |
| --- | --- | --- |
| [vehicle-location-diff](https://github.com/donmahallem/xants/tree/master/packages/vehicle-location-diff) | [![npm version](https://badge.fury.io/js/%40manniwatch%2Fvehicle-location-diff.svg)](https://badge.fury.io/js/%40manniwatch%2Fvehicle-location-diff) | [![codecov](https://codecov.io/gh/donmahallem/xants/branch/master/graph/badge.svg?flag=VehicleLocationDiff)](https://codecov.io/gh/donmahallem/xants/tree/master/packages/vehicle-location-diff) |

## Build & Test
Before you either do both run:

    npm install
    npx lerna bootstrap --no-ci
    npm run build

This project does use [lerna](https://github.com/lerna/lerna) so all common [commands](https://github.com/lerna/lerna/tree/master/commands) should work from the root directory!
Due to packages depending on each other a build is **required** first before running tests!

### Build & Test all packages

    npm run build
    npm run test

### Build & Test a specific package
    npx lerna run build --scope=@donmahallem/xants-app-iot
    npx lerna run test --scope=@donmahallem/xants-app-iot
