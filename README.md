<!-- ⚠️ This README has been generated from the file(s) "readme_blueprint.md" ⚠️-->
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#manniwatch)

# ➤ ManniWatch
<p align="center">
		<a href="https://github.com/donmahallem/xants/actions?query=workflow%3ATest+branch%3Amaster"><img alt="Test" src="https://github.com/donmahallem/xants/workflows/Test/badge.svg?branch=master&event=push" height="20"/></a>
<a href="https://codecov.io/gh/donmahallem/xants/branch/master"><img alt="codecov" src="https://codecov.io/gh/donmahallem/xants/branch/master/graph/badge.svg" height="20"/></a>
<a href="https://github.com/donmahallem/xants/releases"><img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/donmahallem/xants?sort=semver" height="20"/></a>
<a href="https://github.com/donmahallem/xants/blob/master/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/donmahallem/xants" height="20"/></a>
<a href="https://github.com/donmahallem/xants"><img alt="David" src="https://img.shields.io/david/dev/donmahallem/xants" height="20"/></a>
<a href="https://github.com/donmahallem/xants/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors-anon/donmahallem/xants" height="20"/></a>
	</p>


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#packages)

## ➤ Packages
| Package | NPM | Coverage |
| --- | --- | --- |
| [vehicle-location-diff](https://github.com/donmahallem/xants/tree/master/packages/vehicle-location-diff) | [![npm version](https://badge.fury.io/js/%40manniwatch%2Fvehicle-location-diff.svg)](https://badge.fury.io/js/%40manniwatch%2Fvehicle-location-diff) | [![codecov](https://codecov.io/gh/donmahallem/xants/branch/master/graph/badge.svg?flag=VehicleLocationDiff)](https://codecov.io/gh/donmahallem/xants/tree/master/packages/vehicle-location-diff) |


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)](#build--test)

## ➤ Build & Test
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
