<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
# http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

# Release Notes

### 3.0.4 (Oct 27, 2023)

**Fixes:**

* [GH-116](https://github.com/apache/cordova-plugin-screen-orientation/pull/116) fix(android, ios): use clobbers to overwrite `screen.orientation`

**Others:**

* [GH-125](https://github.com/apache/cordova-plugin-screen-orientation/pull/125) dep: bump `word-wrap` from `1.2.3` to `1.2.5`
* [GH-124](https://github.com/apache/cordova-plugin-screen-orientation/pull/124) chore: update asf config
* [GH-123](https://github.com/apache/cordova-plugin-screen-orientation/pull/123) ci(gh-action): sync with paramedic configs

### 3.0.3 (Feb 21, 2023)
* build(deps): bump json5 from 1.0.1 to 1.0.2 ([#110](https://github.com/apache/cordova-plugin-screen-orientation/issues/110))
* feat(ios): add support for **iOS** 16 ([#107](https://github.com/apache/cordova-plugin-screen-orientation/issues/107))
* fix(chrome): lock test ([#105](https://github.com/apache/cordova-plugin-screen-orientation/issues/105))
* chore: add .npmrc file to ensure the official NPM registry is used for package installations. ([#103](https://github.com/apache/cordova-plugin-screen-orientation/issues/103))
* chore: package-lock update (#104)
* ci: sync workflow with paramedic (#101)
* chore(npm): bump package-lock v2 w/ rebuild (#99)
* ci(android): update java requirement for `cordova-android`@11 ([#92](https://github.com/apache/cordova-plugin-screen-orientation/issues/92))
* ci(ios): update workflow w/ **iOS** 15 ([#88](https://github.com/apache/cordova-plugin-screen-orientation/issues/88))
* ci: add action-badge (#87)
* ci: remove travis & appveyor (#86)
* ci: add gh-actions workflows ([#84](https://github.com/apache/cordova-plugin-screen-orientation/issues/84))
* ci: add node-14.x to workflow ([#76](https://github.com/apache/cordova-plugin-screen-orientation/issues/76))
* fix: resolveOrientation function not working correctly ([#77](https://github.com/apache/cordova-plugin-screen-orientation/issues/77))
* ci(travis): update osx xcode image (#72)
* ci(travis): updates **Android** API level (#71)
* chore: adds package-lock file ([#67](https://github.com/apache/cordova-plugin-screen-orientation/issues/67))
* refactor(eslint): use cordova-eslint /w fix ([#66](https://github.com/apache/cordova-plugin-screen-orientation/issues/66))
* chore(npm): use short notation in `package.json` ([#64](https://github.com/apache/cordova-plugin-screen-orientation/issues/64))
* chore: removes old demo project. closes #52 (#65)
* chore(asf): update git notification settings
* Update CONTRIBUTING.md
* chore(npm): improve ignore list ([#60](https://github.com/apache/cordova-plugin-screen-orientation/issues/60))
* ci: updates Node.js versions ([#61](https://github.com/apache/cordova-plugin-screen-orientation/issues/61))
* test: let Jasmine handle promises ([#57](https://github.com/apache/cordova-plugin-screen-orientation/issues/57))
* ci(appveyor): replace node 6 with node 12
* ci(travis): upgrade to node 8
* chore(release): 3.0.3-dev

### 3.0.2 (Jun 19, 2019)

-   fix(ios): Landscape Issue Fix and prevent orientation change when already in orientation ([#25](https://github.com/apache/cordova-plugin-screen-orientation/issues/25)) ([`a89e94c`](https://github.com/apache/cordova-plugin-screen-orientation/commit/a89e94c), [`13b34f0`](https://github.com/apache/cordova-plugin-screen-orientation/commit/13b34f0))
-   build: update `.npmignore` to remove unneeded files from npm package ([`80724df`](https://github.com/apache/cordova-plugin-screen-orientation/commit/80724df))
-   build: add `.gitattributes` to force LF (instead of possible CRLF on Windows) ([`ae60fa9`](https://github.com/apache/cordova-plugin-screen-orientation/commit/ae60fa9))
-   docs: move legacy release notes to `RELEASENOTES.md` ([`34c9c29`](https://github.com/apache/cordova-plugin-screen-orientation/commit/34c9c29))
-   ci(travis): Update Travis CI configuration for new paramedic ([#47](https://github.com/apache/cordova-plugin-screen-orientation/issues/47)) ([`83370a8`](https://github.com/apache/cordova-plugin-screen-orientation/commit/83370a8))
-   chore: add missing keywords to package.json for plugin search ([#49](https://github.com/apache/cordova-plugin-screen-orientation/issues/49)) ([`7f493ce`](https://github.com/apache/cordova-plugin-screen-orientation/commit/7f493ce))
-   ci: drop Node.js v4 support ([#45](https://github.com/apache/cordova-plugin-screen-orientation/issues/45)) ([`de7f6fe`](https://github.com/apache/cordova-plugin-screen-orientation/commit/de7f6fe))
-   chore(github): Add or update GitHub pull request and issue template ([`ccc17fb`](https://github.com/apache/cordova-plugin-screen-orientation/commit/ccc17fb))
-   ci(travis): also accept terms for android sdk `android-27` ([`9d2a422`](https://github.com/apache/cordova-plugin-screen-orientation/commit/9d2a422))
-   chore: [CB-11843](https://issues.apache.org/jira/browse/CB-11843) fix package information ([#33](https://github.com/apache/cordova-plugin-screen-orientation/issues/33)) ([`950d339`](https://github.com/apache/cordova-plugin-screen-orientation/commit/950d339))
-   ci(travis): [CB-13765](https://issues.apache.org/jira/browse/CB-13765) Add build-tools-26.0.2 to travis ([#30](https://github.com/apache/cordova-plugin-screen-orientation/issues/30)) ([`6fd974d`](https://github.com/apache/cordova-plugin-screen-orientation/commit/6fd974d), [`c5802c5`](https://github.com/apache/cordova-plugin-screen-orientation/commit/c5802c5))
-   docs: Fix release notes ([#29](https://github.com/apache/cordova-plugin-screen-orientation/issues/29)) ([`76f290e`](https://github.com/apache/cordova-plugin-screen-orientation/commit/76f290e))


### 3.0.1 (Dec 27, 2017)
* [CB-13710](https://issues.apache.org/jira/browse/CB-13710) Fix to allow 3.0.0 version install (#28)

### 3.0.0 (Dec 15, 2017)
* [CB-13673](https://issues.apache.org/jira/browse/CB-13673) : Remove deprecated platforms
* [CB-13405](https://issues.apache.org/jira/browse/CB-13405) (ios) undo lock when resetting
* [CB-13405](https://issues.apache.org/jira/browse/CB-13405) (ios) Screen unlock bug fix

### 2.0.2 (Nov 06, 2017)
* [CB-13472](https://issues.apache.org/jira/browse/CB-13472) (CI) Fixed Travis **Android** builds again
* [CB-13028](https://issues.apache.org/jira/browse/CB-13028) (CI) **Browser** builds on Travis and AppVeyor
* [CB-12994](https://issues.apache.org/jira/browse/CB-12994) (android, **BlackBerry**) add `es6-promise-plugin` from `npm`
* [CB-12847](https://issues.apache.org/jira/browse/CB-12847) added `bugs` entry to `package.json`.

### 2.0.1 (Apr 27, 2017)
* [CB-12622](https://issues.apache.org/jira/browse/CB-12622) Added **Android 6.0** build badge to `README`
* [CB-12543](https://issues.apache.org/jira/browse/CB-12543) (iOS) Rotate to specified orientation when locked
* [CB-12685](https://issues.apache.org/jira/browse/CB-12685) added `package.json` to tests folder
* [CB-12588](https://issues.apache.org/jira/browse/CB-12588) add manual tests in cordova-plugin-test-framework style

### 2.0.0 (Mar 14, 2017)
* Common javascript for iOS, Android and Windows.
* [CB-11628](https://issues.apache.org/jira/browse/CB-11628) - w3c spec compliance https://www.w3.org/TR/screen-orientation/

### 1.4.2 (Dec 07, 2016)
* [CB-11919](https://issues.apache.org/jira/browse/CB-11919) - Add github pull request template
* Merge pull request #1 from DouglasHSS/master
* updated readme with release notes
* version updated and license adjusted
* support interoperability between Orientation preference and screen-orientation plugin
* fix header file incorrectly set as source-file
* adding missing files to plugin.xml
* make iOS rotate as needed when lockOrientation is called
* switch license from MIT to Apache 2.0

## 1.4.1
* Fix for cordova >= 3.6.3

## 1.4.0
* Added Windows 8.1 Support
* Background thread for ios
* Orientation naming bug fixed
* Add portrait upside down to iOS default orientations

## 1.3.5-6
* Plugin added to npm

## 1.3.4
* Readme update

## 1.3.3
* WP8 Support

## 1.3.2
*  iOS8 Delay Block

## 1.3.0
* iOS8 flicker

## 1.2.0-1.2.1
* iOS8 Crash
