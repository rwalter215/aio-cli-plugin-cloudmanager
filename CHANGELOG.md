# Changelog

## [1.6.2](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.6.1...1.6.2) (2021-04-30)


### Bug Fixes

* **deps:** update aio-lib-cloudmanager for log error message fix. fixes [#300](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/300) ([#301](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/301)) ([9e47144](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/9e47144f559a03604805c4edada8176a071ba8fd))

## [1.6.1](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.6.0...1.6.1) (2021-04-29)


### Bug Fixes

* **hook:** check-ims-config is not correctly throwing errors. fixes [#295](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/295) ([#297](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/297)) ([f2a5768](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/f2a57683531d0dac1368cba038714686ff34b7de))

# [1.6.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.5.1...1.6.0) (2021-04-21)


### Features

* **variables:** show status on list variables table. fixes [#279](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/279) ([76bce13](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/76bce13f00223403bb408121e0de7a6f2e446400))

## [1.5.1](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.5.0...1.5.1) (2021-04-20)


### Bug Fixes

* **hooks:** restore behavior of default environment id. fixes [#280](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/280) ([797f0dd](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/797f0dd18110a012af91fcc2d08b16775afa25da))

# [1.5.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.4.0...1.5.0) (2021-04-13)


### Features

* **execution:** add execution status to current-execution:get. fixes [#275](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/275) ([c1cfd75](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/c1cfd75a9db67f8077a7a8bd1b43f8c1412b6184))

# [1.4.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.6...1.4.0) (2021-04-08)


### Features

* **variables:** support service-specific environment variables. fixes [#268](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/268) ([d0a93ac](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/d0a93ace41df356250e752155d2d2273623e0e20))

## [1.3.6](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.5...1.3.6) (2021-04-01)


### Bug Fixes

* **variables:** ensure that variables validation errors are output. fixes [#262](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/262) ([36a5e1f](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/36a5e1f072c2f35bca4ce821d9c2e3e4fc422378))

## [1.3.5](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.4...1.3.5) (2021-03-26)


### Bug Fixes

* **deps:** force the use of @adobe/aio-lib-ims-jwt higher than 2.1.1 ([de8d6f9](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/de8d6f9ee51ba188bbbf73696dd40b9b7f373a67)), closes [#256](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/256)

## [1.3.4](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.3...1.3.4) (2021-03-22)


### Bug Fixes

* **variables:** fix how numeric values are parsed. fixes [#253](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/253) ([5b9771f](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/5b9771f2b0eb653f5dc7877d93cff3713f8f7273))

## [1.3.3](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.2...1.3.3) (2021-03-09)


### Bug Fixes

* **hook:** check plugin from hookOptions in environment id hook. fixes [#242](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/242) ([6c28117](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/6c28117e269e600cec535c8e3380b06518e18826))

## [1.3.2](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.1...1.3.2) (2021-03-08)


### Bug Fixes

* **hook:** only check ims context on commands for this plugin ([6365e14](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/6365e146595eacbaf62e1ac0dc249fe9a3e2d328))

## [1.3.1](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.3.0...1.3.1) (2021-03-08)


### Bug Fixes

* **hook:** validate ims context configuration from flag. fixes [#237](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/237) ([9d6b1ae](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/9d6b1ae253f3eb804c1b7808cc19d37333082ff6))

# [1.3.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.2.0...1.3.0) (2021-03-05)


### Features

* **config:** add hook for validation of the IMS context configuration. fixes [#233](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/233) and [#216](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/216) ([694523d](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/694523dc0f3e8d50510f15901c13caf4930c7a89))

# [1.2.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.1.1...1.2.0) (2021-02-22)


### Bug Fixes

* **ci:** also ignoring max body length ([92430a8](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/92430a8c12e2f526c00eab4d2084cf25f496ed5f))
* **ci:** another attempt to fix commitlint ([43a1e33](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/43a1e33b5e2da7d9635d476d840f7aab60ca0f48))
* **ci:** disable footer-max-line-length commitlint rule ([ad2bfa6](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/ad2bfa69055d52a9a6ebc7d000d696a2302217fc))


### Features

* support standalone execution. fixes [#219](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/219) ([273d808](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/273d8084011adeebc8b5530f6c5098cda0f99fb7))

## [1.1.1](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.1.0...1.1.1) (2021-02-16)


### Bug Fixes

* **auth:** do not create .aio file in local directory. fixes [#212](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/212) ([ec2a9c2](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/ec2a9c22764b941a5f18005c4bdd405ddc5a1d79))

# [1.1.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/1.0.0...1.1.0) (2021-02-07)


### Features

* **pipeline:** add pipeline:list-executions. fixes [#201](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/201) ([a5968fc](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/a5968fc499d956ad55f85b9213071f1349a3926b))

# [1.0.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.19.0...1.0.0) (2021-02-06)


### Features

* **auth:** replace Migrate from @adobe/aio-cli-plugin-jwt-auth to @adobe/aio-lib-ims ([84abb64](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/84abb641bd3e7b3f92ece3dfb57126c29ddc1079)), closes [#129](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/129)


### BREAKING CHANGES

* **auth:** private key passphrases are no longer supported

# [0.19.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.18.3...0.19.0) (2021-01-13)


### Features

* **ip-allowlists:** implementation of IP Allowlist commands. relates to [#178](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/178) ([6ad76fd](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/6ad76fd8139b3d3fab4a8b6331183f6282c3cf5e))

## [0.18.3](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.18.2...0.18.3) (2021-01-12)


### Bug Fixes

* **deps:** update dependency @adobe/aio-lib-core-config to v2 ([f004835](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/f004835a2030d51c8c5fd49687c03b2baf314ace))

## [0.18.2](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.18.1...0.18.2) (2020-11-19)


### Bug Fixes

* **deps:** update dependency @oclif/plugin-help to v3 ([ed9ad22](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/ed9ad222cb28bddfdfd5a1a975209eb4eedbfedf))

## [0.18.1](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.18.0...0.18.1) (2020-11-18)


### Bug Fixes

* **help:** improve help output. fixes [#165](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/165) ([25ee085](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/25ee085b69dbad040d937f8f60a9c4aeedf8140f))

# [0.18.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.17.0...0.18.0) (2020-11-17)


### Features

* **variables:** support JSON input on stdin and files. fixes [#150](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/150) ([#153](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/153)) ([9ad5b34](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/9ad5b349969ecd7b95f7b83f7bbf573c4d89b77b))

# [0.17.0](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.16.3...0.17.0) (2020-11-17)


### Features

* **various:** implement loading environmentId from configuration. fixes [#149](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/149) ([#154](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/154)) ([c1b0d5e](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/c1b0d5e13f9adb9a976b3d1dad04923f205b1140))

## [0.16.3](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.16.2...0.16.3) (2020-11-16)


### Bug Fixes

* **build:** changelog title not respected ([16c71d4](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/16c71d4a1a30465646bba47c56cb676f3dac85e7))

## [0.16.2](https://github.com/adobe/aio-cli-plugin-cloudmanager/compare/0.16.1...0.16.2) (2020-11-16)

### Bug Fixes

* **build:** semantic-release does not update readme, changelog or package.json in git ([c893959](https://github.com/adobe/aio-cli-plugin-cloudmanager/commit/c893959acc5c3af0efd60a63fa14f6dbbd329045))

## 0.16.0 (13/11/2020)
- [**enhancement**] Restructure commands into topics [#151](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/151)

---

## 0.15.11 (12/11/2020)

- No functional changes. Purely done to change release process.

---

## 0.15.0 (12/11/2020)
- [**enhancement**] Add support for json and yaml output formats [#147](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/147)
-  Replace use of startExecution with createExecution [#145](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/145)

---

## 0.14.1 (15/10/2020)
- [**bug**] Description of tail-log and download-logs is incorrect [#142](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/142)

---

## 0.14.0 (29/09/2020)
-  Allow to use 'e'-prefixed env ids as found in cloud manager URLs [#140](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/140)
- [**enhancement**] Refactor out aio-lib-cloudmanager [#138](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/138)

---

## 0.13.0 (04/09/2020)

- [**enhancement**] Add Support for Experience Audit [#136](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/136)

## 0.12.0 (22/07/2020)
- [**enhancement**] Delete Environment [#133](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/133)

## 0.11.0 (17/07/2020)
- [**enhancement**] Support Pipeline Variables List/Set [#131](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/131)

---

## 0.10.0 (12/06/2020)
- [**enhancement**] Output error code/message when present in error response [#122](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/122)

---

## 0.9.0 (04/06/2020)
-  Support delete program through CLI [#119](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/119)

---

## 0.8.0 (27/05/2020)
-  Include validation errors in the non-debug error message [#115](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/115)
-  Remove dependency on aio-cli-plugin-runtime [#111](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/111)
-  resolve depcheck warnings [#109](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/109)

---

## 0.7.3 (27/04/2020)
-  cloudmanager:base-environment-variables-command should not be listed on readme [#101](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/101)

---

## 0.7.2 (21/04/2020)
-  Cancelling a paused deployment needs to use the advance, not cancel endpoint [#99](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/99)

---

## 0.7.1 (10/04/2020)
- [**bug**] Secret environment variables cannot be deleted [#96](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/96)

---

## 0.7.0 (26/02/2020)
- [**enhancement**] Add support for alternate files in get-execution-step-logs [#84](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/84)

---

## 0.6.2 (24/02/2020)
- [**enhancement**] DEBUG mode should output result body for errors [#80](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/80)

---

## 0.6.1 (20/02/2020)
-  when outputting variables after setting them cloudmanager:set-environment-variables doesn't output secrets properly [#78](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/78)

---

## 0.6.0 (20/02/2020)
-  Add support for listing/setting environment variables [#76](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/76)

---

## 0.5.2 (13/12/2019)
-  Switch from @adobe/aio-cna-core-config to @adobe/aio-lib-core-config wasn't done in tests [#65](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/65)

---

## 0.5.1 (12/12/2019)
-  Miscellaneous warnings when installing plugin [#61](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/61)

---

## 0.5.0 (12/12/2019)
-  Add Open Developer Console Command [#59](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/59)

---

## 0.4.0 (10/12/2019)
-  Ease setting pipeline to a tag [#57](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/57)
-  list-environments displays undefined for description [#54](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/54)

---

## 0.3.3 (11/11/2019)
-  Improve console output when no log options [#51](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/51)

---

## 0.3.2 (29/10/2019)
*No changelog for this release.*

---

## 0.3.1 (22/10/2019)
*No changelog for this release.*

---

## 0.3.0 (18/10/2019)
-  aio cloudmanager is not complete help [#44](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/44)
- [**enhancement**] add support for editing pipeline branch  [#42](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/42)
- [**enhancement**] Add support for deleting pipelines via CLI [#41](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/41)

---

## 0.2.1 (10/10/2019)
-  Require node 10 [#39](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/39)

---

## 0.2.0 (10/10/2019)
-  Add a command to get the logs for a step [#35](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/35)

---

## 0.1.6 (03/10/2019)
*No changelog for this release.*

---

## 0.1.5 (27/09/2019)
-  Should be a get execution details command [#32](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/32)

---

## 0.1.4 (13/09/2019)
-  Add support for listing environments [#30](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/30)

---

## 0.1.3 (20/08/2019)
-  Use templated execution link to get execution [#25](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/25)

---

## 0.1.2 (19/08/2019)
*No changelog for this release.*

---

## 0.1.1 (08/08/2019)
*No changelog for this release.*

---

## 0.1.0 (06/08/2019)
-  When starting an execution, the execution id should be output on the CLI [#19](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/19)

---

## 0.0.5 (23/07/2019)
- [**bug**] aio cloudmanager prints error [#16](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/16)

---

## 0.0.4 (09/07/2019)
-  Add cancel and advance commands [#7](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/7)

---

## 0.0.3 (08/07/2019)
-  plugin description is incorrect [#5](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/5)
-  add get-quality-gate-results command [#2](https://github.com/adobe/aio-cli-plugin-cloudmanager/issues/2)

---

## 0.0.2 (04/06/2019)
*No changelog for this release.*

---

## 0.0.1 (31/05/2019)
*No changelog for this release.*
