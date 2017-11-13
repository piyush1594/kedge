# Change Log

## [v0.4.0](https://github.com/kedgeproject/kedge/tree/v0.4.0) (2017-10-31)
[Full Changelog](https://github.com/kedgeproject/kedge/compare/v0.3.0...v0.4.0)

**Closed issues:**

- kedge init generates invalid  kedge file [\#396](https://github.com/kedgeproject/kedge/issues/396)
- All e2e tests are broken - semaphore is showing false positives [\#371](https://github.com/kedgeproject/kedge/issues/371)
- Reduce size of repository [\#362](https://github.com/kedgeproject/kedge/issues/362)
- DeploymentConfig defaults to 0 replicas, should be 1 [\#359](https://github.com/kedgeproject/kedge/issues/359)
- replicas set to 0 if not specified [\#357](https://github.com/kedgeproject/kedge/issues/357)
- generated  DeploymnetConfig is invalid! [\#352](https://github.com/kedgeproject/kedge/issues/352)
- Figure out GVK mechanism for OpenShift [\#349](https://github.com/kedgeproject/kedge/issues/349)
- e2e test invocation script passes even if test fails [\#348](https://github.com/kedgeproject/kedge/issues/348)
- use oc insetad of kubectl for OpenShift artifacts [\#341](https://github.com/kedgeproject/kedge/issues/341)
- some tests don't run when you do `make test` [\#333](https://github.com/kedgeproject/kedge/issues/333)
- create job using kedge init [\#325](https://github.com/kedgeproject/kedge/issues/325)
- name service ports to make it work with openshift routes [\#323](https://github.com/kedgeproject/kedge/issues/323)
- add flag `--save-config` to `kubectl create` [\#322](https://github.com/kedgeproject/kedge/issues/322)
- General UX/UI/Website update tracking card [\#268](https://github.com/kedgeproject/kedge/issues/268)
- stop emulating envFrom and start using it directly [\#248](https://github.com/kedgeproject/kedge/issues/248)
- Support OpenShift Routes [\#238](https://github.com/kedgeproject/kedge/issues/238)

**Merged pull requests:**

- Update release script for introduction.md [\#400](https://github.com/kedgeproject/kedge/pull/400) ([cdrage](https://github.com/cdrage))
- kedge init: fix wrong type for ports [\#399](https://github.com/kedgeproject/kedge/pull/399) ([kadel](https://github.com/kadel))
- Update Makefile [\#398](https://github.com/kedgeproject/kedge/pull/398) ([bs34](https://github.com/bs34))
- fix broken semaphore badge [\#395](https://github.com/kedgeproject/kedge/pull/395) ([containscafeine](https://github.com/containscafeine))
- Update encrypted deploy key [\#393](https://github.com/kedgeproject/kedge/pull/393) ([cdrage](https://github.com/cdrage))
- Update the docs to reflect 0.3.0 [\#392](https://github.com/kedgeproject/kedge/pull/392) ([cdrage](https://github.com/cdrage))
- Add semaphore badge to README [\#391](https://github.com/kedgeproject/kedge/pull/391) ([cdrage](https://github.com/cdrage))
- Remove .enc extension from release script [\#389](https://github.com/kedgeproject/kedge/pull/389) ([cdrage](https://github.com/cdrage))
- Sync docs with gh-pages [\#387](https://github.com/kedgeproject/kedge/pull/387) ([cdrage](https://github.com/cdrage))
- few small updates to travis.yml [\#386](https://github.com/kedgeproject/kedge/pull/386) ([kadel](https://github.com/kadel))
- always populate service port name [\#384](https://github.com/kedgeproject/kedge/pull/384) ([surajssd](https://github.com/surajssd))
- Replace all occurrences of spec.go with types.go [\#382](https://github.com/kedgeproject/kedge/pull/382) ([surajssd](https://github.com/surajssd))
- Revert "always populate service port name" [\#380](https://github.com/kedgeproject/kedge/pull/380) ([containscafeine](https://github.com/containscafeine))
- Change the json schema testing from spec.go to types.go [\#378](https://github.com/kedgeproject/kedge/pull/378) ([surajssd](https://github.com/surajssd))
- move e2e test invocation script to scripts [\#374](https://github.com/kedgeproject/kedge/pull/374) ([surajssd](https://github.com/surajssd))
- fix\(e2e tests\): make test compile [\#372](https://github.com/kedgeproject/kedge/pull/372) ([surajssd](https://github.com/surajssd))
- don't show error when building from tarball [\#370](https://github.com/kedgeproject/kedge/pull/370) ([kadel](https://github.com/kadel))
- Divide ingress example to 2 parts [\#369](https://github.com/kedgeproject/kedge/pull/369) ([containscafeine](https://github.com/containscafeine))
- add OpenShift Apps scheme for DeploymentConfig [\#368](https://github.com/kedgeproject/kedge/pull/368) ([containscafeine](https://github.com/containscafeine))
- add support for OpenShift Routes [\#366](https://github.com/kedgeproject/kedge/pull/366) ([containscafeine](https://github.com/containscafeine))
- use oc instead of kubectl for OpenShift artefacts [\#365](https://github.com/kedgeproject/kedge/pull/365) ([kadel](https://github.com/kadel))
- Fix e2e wrapper script to return exit status of e2e tests [\#364](https://github.com/kedgeproject/kedge/pull/364) ([ashetty1](https://github.com/ashetty1))
- set default replicas as 1 in DeploymentConfig [\#361](https://github.com/kedgeproject/kedge/pull/361) ([containscafeine](https://github.com/containscafeine))
- Remove --distribution flag [\#360](https://github.com/kedgeproject/kedge/pull/360) ([cdrage](https://github.com/cdrage))
- fix\(dc\): populate labels rightfully [\#355](https://github.com/kedgeproject/kedge/pull/355) ([surajssd](https://github.com/surajssd))
- \(kedge init\): add flag --controller [\#353](https://github.com/kedgeproject/kedge/pull/353) ([surajssd](https://github.com/surajssd))
- fix error message for creating DeploymentConfig [\#351](https://github.com/kedgeproject/kedge/pull/351) ([containscafeine](https://github.com/containscafeine))
- always populate service port name [\#346](https://github.com/kedgeproject/kedge/pull/346) ([surajssd](https://github.com/surajssd))
- remove envFrom expansion support [\#345](https://github.com/kedgeproject/kedge/pull/345) ([surajssd](https://github.com/surajssd))
- fix\(kedge create\): add flag `--save-config` [\#344](https://github.com/kedgeproject/kedge/pull/344) ([surajssd](https://github.com/surajssd))
- fix\(travis\): don't test on go1.6 [\#342](https://github.com/kedgeproject/kedge/pull/342) ([surajssd](https://github.com/surajssd))
- Change vendoring script to bash from sh [\#338](https://github.com/kedgeproject/kedge/pull/338) ([cdrage](https://github.com/cdrage))
- add coverage test to normal test runs [\#336](https://github.com/kedgeproject/kedge/pull/336) ([surajssd](https://github.com/surajssd))
- Remove changes.txt [\#330](https://github.com/kedgeproject/kedge/pull/330) ([cdrage](https://github.com/cdrage))
- add local testing of json schema generation [\#316](https://github.com/kedgeproject/kedge/pull/316) ([surajssd](https://github.com/surajssd))
- Add DeploymentConfig support [\#315](https://github.com/kedgeproject/kedge/pull/315) ([cdrage](https://github.com/cdrage))

## [v0.3.0](https://github.com/kedgeproject/kedge/tree/v0.3.0) (2017-10-10)
[Full Changelog](https://github.com/kedgeproject/kedge/compare/v0.2.0...v0.3.0)

**Closed issues:**

- Generating Kedge maifests from Kubernetes and OpenShift [\#321](https://github.com/kedgeproject/kedge/issues/321)
- Name is not propagated to single Ingress [\#306](https://github.com/kedgeproject/kedge/issues/306)
- imagePullSecrets are dropped on the floor [\#304](https://github.com/kedgeproject/kedge/issues/304)
- `kedge build` subcommand which is alias to docker build [\#287](https://github.com/kedgeproject/kedge/issues/287)
- Add annotations support [\#262](https://github.com/kedgeproject/kedge/issues/262)
- version numbers / image tags in kedge YAML [\#224](https://github.com/kedgeproject/kedge/issues/224)
- Rename `extraResources` to `includeResources` [\#218](https://github.com/kedgeproject/kedge/issues/218)
- "Introduce root level `controller` field", and sub tasks [\#188](https://github.com/kedgeproject/kedge/issues/188)
- Jobs do not support activeDeadlineSeconds [\#114](https://github.com/kedgeproject/kedge/issues/114)
- Jobs will not support populating container names, we need to support that [\#113](https://github.com/kedgeproject/kedge/issues/113)
- abstract out kedge "populators" [\#98](https://github.com/kedgeproject/kedge/issues/98)
- our build story [\#89](https://github.com/kedgeproject/kedge/issues/89)
- e2e tests - test conversions on running cluster [\#59](https://github.com/kedgeproject/kedge/issues/59)
- Add travis/fabric8 CI support for PR building [\#57](https://github.com/kedgeproject/kedge/issues/57)
- Add unit tests [\#56](https://github.com/kedgeproject/kedge/issues/56)
- Add support for defining `Job` controller [\#52](https://github.com/kedgeproject/kedge/issues/52)
- Decouple injecting default values from the generation code [\#50](https://github.com/kedgeproject/kedge/issues/50)
- Decouple validation from generation code [\#49](https://github.com/kedgeproject/kedge/issues/49)
- generate a json-schema file [\#45](https://github.com/kedgeproject/kedge/issues/45)
- Add testing \(unit, conversion & e2e testing\) [\#24](https://github.com/kedgeproject/kedge/issues/24)
- defining configmap/secret data in a way that auto-creates the container env vars [\#2](https://github.com/kedgeproject/kedge/issues/2)

**Merged pull requests:**

- 0.3.0 Release [\#329](https://github.com/kedgeproject/kedge/pull/329) ([cdrage](https://github.com/cdrage))
- fix\(spec\): add optional tag in struct fields [\#311](https://github.com/kedgeproject/kedge/pull/311) ([surajssd](https://github.com/surajssd))
- auto populate ingress name [\#310](https://github.com/kedgeproject/kedge/pull/310) ([containscafeine](https://github.com/containscafeine))
- pin down apimachinery with a git commit [\#303](https://github.com/kedgeproject/kedge/pull/303) ([surajssd](https://github.com/surajssd))
- Move to old logrus version 0.7.3 [\#302](https://github.com/kedgeproject/kedge/pull/302) ([surajssd](https://github.com/surajssd))
- Add support for environment variable substitution [\#300](https://github.com/kedgeproject/kedge/pull/300) ([kadel](https://github.com/kadel))
- Add OpenShift vendoring [\#299](https://github.com/kedgeproject/kedge/pull/299) ([kadel](https://github.com/kadel))
- make indentation uniform in example file [\#298](https://github.com/kedgeproject/kedge/pull/298) ([containscafeine](https://github.com/containscafeine))
- Update vendor logrus [\#296](https://github.com/kedgeproject/kedge/pull/296) ([surajssd](https://github.com/surajssd))
- \(feat\): build docker images using, `kedge build` [\#295](https://github.com/kedgeproject/kedge/pull/295) ([surajssd](https://github.com/surajssd))
- Reworks layout + index output [\#294](https://github.com/kedgeproject/kedge/pull/294) ([cdrage](https://github.com/cdrage))
- fix broken example links in readme [\#292](https://github.com/kedgeproject/kedge/pull/292) ([jdolitsky](https://github.com/jdolitsky))
- spec change: rename `extraResources` to `includeResources` [\#291](https://github.com/kedgeproject/kedge/pull/291) ([surajssd](https://github.com/surajssd))
- Make website more minimal, remove colours+whale [\#289](https://github.com/kedgeproject/kedge/pull/289) ([cdrage](https://github.com/cdrage))
- Minor fixes [\#283](https://github.com/kedgeproject/kedge/pull/283) ([cdrage](https://github.com/cdrage))
- Redesign site + adds logo [\#282](https://github.com/kedgeproject/kedge/pull/282) ([cdrage](https://github.com/cdrage))
- add license to Makefile [\#281](https://github.com/kedgeproject/kedge/pull/281) ([surajssd](https://github.com/surajssd))
- Added error handling in cmd/init.go [\#279](https://github.com/kedgeproject/kedge/pull/279) ([surajnarwade](https://github.com/surajnarwade))
- Script to display live output from e2e tests [\#275](https://github.com/kedgeproject/kedge/pull/275) ([ashetty1](https://github.com/ashetty1))
- merge ObjectMeta with ControllerFields [\#267](https://github.com/kedgeproject/kedge/pull/267) ([containscafeine](https://github.com/containscafeine))

## [v0.2.0](https://github.com/kedgeproject/kedge/tree/v0.2.0) (2017-09-18)
[Full Changelog](https://github.com/kedgeproject/kedge/compare/v0.1.0...v0.2.0)

**Closed issues:**

- more frequent releases? [\#277](https://github.com/kedgeproject/kedge/issues/277)
- Add `--distribution` flag [\#245](https://github.com/kedgeproject/kedge/issues/245)
- Make controller a field in App struct [\#233](https://github.com/kedgeproject/kedge/issues/233)
- kedge init should not allow non int values for port [\#231](https://github.com/kedgeproject/kedge/issues/231)
- Reference Helm Chart from Kedge file [\#217](https://github.com/kedgeproject/kedge/issues/217)
- shortcut for port [\#216](https://github.com/kedgeproject/kedge/issues/216)
- kedge init [\#215](https://github.com/kedgeproject/kedge/issues/215)
- Add go report badge [\#209](https://github.com/kedgeproject/kedge/issues/209)
- Order of the outputted artifacts [\#207](https://github.com/kedgeproject/kedge/issues/207)
- Example in allnomagic does not work [\#203](https://github.com/kedgeproject/kedge/issues/203)
- Is mention bot providing any value? [\#159](https://github.com/kedgeproject/kedge/issues/159)
- Add kedge delete to use guide [\#145](https://github.com/kedgeproject/kedge/issues/145)
- Add installation document after a release [\#140](https://github.com/kedgeproject/kedge/issues/140)
- \[spec change\] Make containers a subkey [\#119](https://github.com/kedgeproject/kedge/issues/119)
- Change 'type' name, related to NodePort, ClusterIP, LoadBalancer, ExternalName to `expose`. [\#103](https://github.com/kedgeproject/kedge/issues/103)
- Update examples and associated readmes [\#60](https://github.com/kedgeproject/kedge/issues/60)
- Add checks for multiple pvc with same name [\#55](https://github.com/kedgeproject/kedge/issues/55)
- Find a better convention referencing env vars in container spec [\#16](https://github.com/kedgeproject/kedge/issues/16)

**Merged pull requests:**

- 0.2.0 Release [\#278](https://github.com/kedgeproject/kedge/pull/278) ([cdrage](https://github.com/cdrage))
- Fix order of controller functions [\#266](https://github.com/kedgeproject/kedge/pull/266) ([cdrage](https://github.com/cdrage))
- Increase ping timeout for e2e tests [\#264](https://github.com/kedgeproject/kedge/pull/264) ([cdrage](https://github.com/cdrage))
- Add timeout param to make test-e2e [\#263](https://github.com/kedgeproject/kedge/pull/263) ([cdrage](https://github.com/cdrage))
- change from DeploymentSpec to DeploymentSpecMod [\#261](https://github.com/kedgeproject/kedge/pull/261) ([surajssd](https://github.com/surajssd))
- docs: add conventions to consider while development [\#260](https://github.com/kedgeproject/kedge/pull/260) ([surajssd](https://github.com/surajssd))
- docs: instructions to add tests, examples and docs [\#259](https://github.com/kedgeproject/kedge/pull/259) ([surajssd](https://github.com/surajssd))
- docs: define go import convention [\#258](https://github.com/kedgeproject/kedge/pull/258) ([surajssd](https://github.com/surajssd))
- Update e2e test files [\#256](https://github.com/kedgeproject/kedge/pull/256) ([cdrage](https://github.com/cdrage))
- move validateVolumeClaims\(\) to resources.go [\#255](https://github.com/kedgeproject/kedge/pull/255) ([containscafeine](https://github.com/containscafeine))
- fix typo in word 'overwrite' [\#254](https://github.com/kedgeproject/kedge/pull/254) ([containscafeine](https://github.com/containscafeine))
- add support for Job controller [\#253](https://github.com/kedgeproject/kedge/pull/253) ([containscafeine](https://github.com/containscafeine))
- Fix spelling / grammar error within init.go [\#252](https://github.com/kedgeproject/kedge/pull/252) ([cdrage](https://github.com/cdrage))
- Update README within examples [\#251](https://github.com/kedgeproject/kedge/pull/251) ([cdrage](https://github.com/cdrage))
- Adds --distribution flag, refactor k8s generation [\#250](https://github.com/kedgeproject/kedge/pull/250) ([cdrage](https://github.com/cdrage))
- Update help info [\#249](https://github.com/kedgeproject/kedge/pull/249) ([cdrage](https://github.com/cdrage))
- update client-go to v4.0.0 [\#246](https://github.com/kedgeproject/kedge/pull/246) ([containscafeine](https://github.com/containscafeine))
- Add Kubernetes cluster script [\#244](https://github.com/kedgeproject/kedge/pull/244) ([cdrage](https://github.com/cdrage))
- update glide-vc instructions to use lock file [\#243](https://github.com/kedgeproject/kedge/pull/243) ([surajssd](https://github.com/surajssd))
- introduce portMappings shortcut [\#242](https://github.com/kedgeproject/kedge/pull/242) ([containscafeine](https://github.com/containscafeine))
- add tags to help generate openAPI schema [\#241](https://github.com/kedgeproject/kedge/pull/241) ([surajssd](https://github.com/surajssd))
- add controller field in app struct [\#240](https://github.com/kedgeproject/kedge/pull/240) ([surajssd](https://github.com/surajssd))
- Add comments to spec.go [\#239](https://github.com/kedgeproject/kedge/pull/239) ([surajssd](https://github.com/surajssd))
- introduce controller interface [\#236](https://github.com/kedgeproject/kedge/pull/236) ([containscafeine](https://github.com/containscafeine))
- Small fixes in the readme. [\#234](https://github.com/kedgeproject/kedge/pull/234) ([pradeepto](https://github.com/pradeepto))
- Fixed port issue in `kedge init` [\#232](https://github.com/kedgeproject/kedge/pull/232) ([surajnarwade](https://github.com/surajnarwade))
- move files from package kubernetes to package spec [\#229](https://github.com/kedgeproject/kedge/pull/229) ([containscafeine](https://github.com/containscafeine))
- Added feature for kedge init [\#228](https://github.com/kedgeproject/kedge/pull/228) ([surajnarwade](https://github.com/surajnarwade))
- move files from package encoding to package spec [\#226](https://github.com/kedgeproject/kedge/pull/226) ([containscafeine](https://github.com/containscafeine))
- change glide.yml to glide.yaml in docs [\#225](https://github.com/kedgeproject/kedge/pull/225) ([surajssd](https://github.com/surajssd))
- Cleanup and reorganize examples [\#222](https://github.com/kedgeproject/kedge/pull/222) ([kadel](https://github.com/kadel))
- Added `kedge delete` in user-guide [\#220](https://github.com/kedgeproject/kedge/pull/220) ([surajnarwade](https://github.com/surajnarwade))
- pass only required parameter to functions [\#214](https://github.com/kedgeproject/kedge/pull/214) ([surajssd](https://github.com/surajssd))
- add license to all the new files [\#213](https://github.com/kedgeproject/kedge/pull/213) ([surajssd](https://github.com/surajssd))
- order artifacts generation [\#212](https://github.com/kedgeproject/kedge/pull/212) ([surajssd](https://github.com/surajssd))
- Added GoReportcard badge [\#211](https://github.com/kedgeproject/kedge/pull/211) ([surajnarwade](https://github.com/surajnarwade))
- move populate volume to populators [\#208](https://github.com/kedgeproject/kedge/pull/208) ([surajssd](https://github.com/surajssd))
- move volume search functions to util [\#206](https://github.com/kedgeproject/kedge/pull/206) ([surajssd](https://github.com/surajssd))
- Fixed allnomagic example [\#205](https://github.com/kedgeproject/kedge/pull/205) ([surajnarwade](https://github.com/surajnarwade))
- check for duplicate volumeClaim definition [\#204](https://github.com/kedgeproject/kedge/pull/204) ([surajssd](https://github.com/surajssd))
- update single file readme and examples readme [\#202](https://github.com/kedgeproject/kedge/pull/202) ([surajssd](https://github.com/surajssd))
- Small docs update - add info about default controller and fix formatting [\#200](https://github.com/kedgeproject/kedge/pull/200) ([kadel](https://github.com/kadel))
- Ignore the bin folder [\#198](https://github.com/kedgeproject/kedge/pull/198) ([cdrage](https://github.com/cdrage))
- Added gitlab example [\#170](https://github.com/kedgeproject/kedge/pull/170) ([surajnarwade](https://github.com/surajnarwade))
- e2e test framework [\#77](https://github.com/kedgeproject/kedge/pull/77) ([surajssd](https://github.com/surajssd))

## [v0.1.0](https://github.com/kedgeproject/kedge/tree/v0.1.0) (2017-08-04)
**Closed issues:**

- We need a badge that shows coverage on homepage [\#193](https://github.com/kedgeproject/kedge/issues/193)
- change init-containers to be list of our modified container struct [\#176](https://github.com/kedgeproject/kedge/issues/176)
- Wordpress examples don't seem to work. [\#167](https://github.com/kedgeproject/kedge/issues/167)
- Add curl commands to download binaries [\#162](https://github.com/kedgeproject/kedge/issues/162)
- Allow adding Kubernetes artifacts to Kedge file. [\#157](https://github.com/kedgeproject/kedge/issues/157)
- Allow passing whole directory as argument for `-f` [\#155](https://github.com/kedgeproject/kedge/issues/155)
- Introducing: "kedge apply" [\#153](https://github.com/kedgeproject/kedge/issues/153)
- rename deploy and undeploy to create and delete [\#150](https://github.com/kedgeproject/kedge/issues/150)
- Add bash/zsh completion support [\#148](https://github.com/kedgeproject/kedge/issues/148)
- Make kedge.yaml as the default file [\#147](https://github.com/kedgeproject/kedge/issues/147)
- Add nightlies [\#139](https://github.com/kedgeproject/kedge/issues/139)
- New "tagline" [\#134](https://github.com/kedgeproject/kedge/issues/134)
- Defining secrets [\#128](https://github.com/kedgeproject/kedge/issues/128)
- Abstract PodSpec and Container to PodSpecMod [\#112](https://github.com/kedgeproject/kedge/issues/112)
- Find conflicting fields programatically [\#111](https://github.com/kedgeproject/kedge/issues/111)
- Empty deployment gets generated when any invalid yaml data is passed [\#109](https://github.com/kedgeproject/kedge/issues/109)
- make test fails [\#105](https://github.com/kedgeproject/kedge/issues/105)
- deprecate replicas in the app struct [\#100](https://github.com/kedgeproject/kedge/issues/100)
- Running `kedge generate/deploy` returns nothing, expected error [\#96](https://github.com/kedgeproject/kedge/issues/96)
- flag to deploy to specific namespace [\#93](https://github.com/kedgeproject/kedge/issues/93)
- `kedge deploy` does not parse a multi-app file [\#91](https://github.com/kedgeproject/kedge/issues/91)
- Add support for envFrom for secrets [\#85](https://github.com/kedgeproject/kedge/issues/85)
- Update client-go to "3.0" [\#81](https://github.com/kedgeproject/kedge/issues/81)
- add subcommand version [\#80](https://github.com/kedgeproject/kedge/issues/80)
- rename top level ingress to ingresses [\#78](https://github.com/kedgeproject/kedge/issues/78)
- Clean up the tests in `encoding\_test.go` [\#69](https://github.com/kedgeproject/kedge/issues/69)
- Update Readme [\#67](https://github.com/kedgeproject/kedge/issues/67)
- Create communication channels and update readme etc. [\#64](https://github.com/kedgeproject/kedge/issues/64)
- CONTRIBUTING file: add process of PR merging [\#63](https://github.com/kedgeproject/kedge/issues/63)
- CONTRIBUTING file: add general contributor's section [\#61](https://github.com/kedgeproject/kedge/issues/61)
- add deploy command [\#54](https://github.com/kedgeproject/kedge/issues/54)
- Rename persistentVolumes to something better [\#51](https://github.com/kedgeproject/kedge/issues/51)
- Add an appropriate licence for the project and files. [\#46](https://github.com/kedgeproject/kedge/issues/46)
- Add support for envFrom for configMaps [\#43](https://github.com/kedgeproject/kedge/issues/43)
- Wrong port number when multiple ports specified  [\#39](https://github.com/kedgeproject/kedge/issues/39)
- Autogenerating port names [\#38](https://github.com/kedgeproject/kedge/issues/38)
- Implement DeploymentSpec in our spec [\#35](https://github.com/kedgeproject/kedge/issues/35)
- volume entry in PodSpec is generated every time volume is used [\#34](https://github.com/kedgeproject/kedge/issues/34)
- Top level name is not propagated to single service [\#33](https://github.com/kedgeproject/kedge/issues/33)
- Two containers in same Pod without name should throw error [\#32](https://github.com/kedgeproject/kedge/issues/32)
- Only health at container level [\#23](https://github.com/kedgeproject/kedge/issues/23)
- Flag to decide whether to expose externally or not [\#22](https://github.com/kedgeproject/kedge/issues/22)
- A better way to define Service ports [\#19](https://github.com/kedgeproject/kedge/issues/19)
- Thoughts on refactoring Services in the spec [\#18](https://github.com/kedgeproject/kedge/issues/18)
- Defining applications in a single file [\#17](https://github.com/kedgeproject/kedge/issues/17)
- Write a rough file-reference.md so we know where the spec is right now [\#15](https://github.com/kedgeproject/kedge/issues/15)
- Volume definition needs to done better [\#14](https://github.com/kedgeproject/kedge/issues/14)
- Root level services are confusing so find a better name for it, also consider moving it somewhere else. [\#13](https://github.com/kedgeproject/kedge/issues/13)
- A better and relevant name for this project [\#9](https://github.com/kedgeproject/kedge/issues/9)

**Merged pull requests:**

- 0.1.0 Release [\#197](https://github.com/kedgeproject/kedge/pull/197) ([cdrage](https://github.com/cdrage))
- Add release script [\#196](https://github.com/kedgeproject/kedge/pull/196) ([cdrage](https://github.com/cdrage))
- introduce an optional root level controller field [\#195](https://github.com/kedgeproject/kedge/pull/195) ([containscafeine](https://github.com/containscafeine))
- Added coverage badge [\#194](https://github.com/kedgeproject/kedge/pull/194) ([surajnarwade](https://github.com/surajnarwade))
- Abstract out the containers population of health and envFrom [\#190](https://github.com/kedgeproject/kedge/pull/190) ([surajssd](https://github.com/surajssd))
- Use kedge defined containers list for init containers [\#189](https://github.com/kedgeproject/kedge/pull/189) ([surajssd](https://github.com/surajssd))
- remove apostrophe to fix typo in word "its" [\#187](https://github.com/kedgeproject/kedge/pull/187) ([containscafeine](https://github.com/containscafeine))
- Use upstream envFromSource than our created ones [\#186](https://github.com/kedgeproject/kedge/pull/186) ([surajssd](https://github.com/surajssd))
- update glide usage docs [\#182](https://github.com/kedgeproject/kedge/pull/182) ([surajssd](https://github.com/surajssd))
- Update client go to 3.0.0 [\#181](https://github.com/kedgeproject/kedge/pull/181) ([surajssd](https://github.com/surajssd))
- clean up test fixtures with test code [\#180](https://github.com/kedgeproject/kedge/pull/180) ([surajssd](https://github.com/surajssd))
- move containers fixing code to its function [\#179](https://github.com/kedgeproject/kedge/pull/179) ([surajssd](https://github.com/surajssd))
- refactor to reuse same InputFiles variable [\#178](https://github.com/kedgeproject/kedge/pull/178) ([containscafeine](https://github.com/containscafeine))
- add files passed check to apply.go [\#177](https://github.com/kedgeproject/kedge/pull/177) ([containscafeine](https://github.com/containscafeine))
- add license to completion.go [\#175](https://github.com/kedgeproject/kedge/pull/175) ([surajssd](https://github.com/surajssd))
- implement namespace specific cluster operations [\#174](https://github.com/kedgeproject/kedge/pull/174) ([containscafeine](https://github.com/containscafeine))
- feat\(spec\): add support for extraResources [\#173](https://github.com/kedgeproject/kedge/pull/173) ([surajssd](https://github.com/surajssd))
- add support to save file name with file data [\#172](https://github.com/kedgeproject/kedge/pull/172) ([surajssd](https://github.com/surajssd))
- define root level secrets and envFrom support [\#171](https://github.com/kedgeproject/kedge/pull/171) ([containscafeine](https://github.com/containscafeine))
- Added bash/zsh autocompletion support [\#169](https://github.com/kedgeproject/kedge/pull/169) ([surajnarwade](https://github.com/surajnarwade))
-  allow passing whole directory as -f argument [\#166](https://github.com/kedgeproject/kedge/pull/166) ([kadel](https://github.com/kadel))
- Update README with curl instructions for Kedge download [\#165](https://github.com/kedgeproject/kedge/pull/165) ([cdrage](https://github.com/cdrage))
- replace errors.New\(fmt.Sprintf\(...\)\) with fmt.Errorf\(...\) [\#163](https://github.com/kedgeproject/kedge/pull/163) ([kadel](https://github.com/kadel))
- Make mention bot less aggressive [\#161](https://github.com/kedgeproject/kedge/pull/161) ([cdrage](https://github.com/cdrage))
- fix indentation of example shown in readme [\#158](https://github.com/kedgeproject/kedge/pull/158) ([surajssd](https://github.com/surajssd))
- Add 'apply' command. [\#156](https://github.com/kedgeproject/kedge/pull/156) ([kadel](https://github.com/kadel))
- Upload binaries to Bintray [\#154](https://github.com/kedgeproject/kedge/pull/154) ([kadel](https://github.com/kadel))
- rename persistentVolumes to volumeClaims [\#152](https://github.com/kedgeproject/kedge/pull/152) ([containscafeine](https://github.com/containscafeine))
- kedge \<subcommand\> errors out without -f/--files [\#151](https://github.com/kedgeproject/kedge/pull/151) ([containscafeine](https://github.com/containscafeine))
- Remove replicas from main app struct [\#149](https://github.com/kedgeproject/kedge/pull/149) ([surajssd](https://github.com/surajssd))
- Update mention bot config [\#143](https://github.com/kedgeproject/kedge/pull/143) ([cdrage](https://github.com/cdrage))
- Rename commands from deploy/undeploy to create/delete [\#142](https://github.com/kedgeproject/kedge/pull/142) ([cdrage](https://github.com/cdrage))
- Add mention bot [\#138](https://github.com/kedgeproject/kedge/pull/138) ([cdrage](https://github.com/cdrage))
- Add quickstart guide [\#137](https://github.com/kedgeproject/kedge/pull/137) ([cdrage](https://github.com/cdrage))
- auto detect conflicting tags [\#135](https://github.com/kedgeproject/kedge/pull/135) ([containscafeine](https://github.com/containscafeine))
- Fix travis [\#132](https://github.com/kedgeproject/kedge/pull/132) ([cdrage](https://github.com/cdrage))
- Add widgets and slack [\#131](https://github.com/kedgeproject/kedge/pull/131) ([cdrage](https://github.com/cdrage))
- Add user-guide and update README. [\#130](https://github.com/kedgeproject/kedge/pull/130) ([cdrage](https://github.com/cdrage))
- Adds an undeploy command [\#129](https://github.com/kedgeproject/kedge/pull/129) ([cdrage](https://github.com/cdrage))
- Italics -\> Bold [\#127](https://github.com/kedgeproject/kedge/pull/127) ([cdrage](https://github.com/cdrage))
- fix some typos [\#126](https://github.com/kedgeproject/kedge/pull/126) ([containscafeine](https://github.com/containscafeine))
- add PR review guidelines [\#125](https://github.com/kedgeproject/kedge/pull/125) ([surajssd](https://github.com/surajssd))
- error out if invalid input data is passed [\#124](https://github.com/kedgeproject/kedge/pull/124) ([containscafeine](https://github.com/containscafeine))
- Updates comments [\#122](https://github.com/kedgeproject/kedge/pull/122) ([cdrage](https://github.com/cdrage))
- Add version command [\#121](https://github.com/kedgeproject/kedge/pull/121) ([cdrage](https://github.com/cdrage))
- fix typo in the word "also" [\#120](https://github.com/kedgeproject/kedge/pull/120) ([containscafeine](https://github.com/containscafeine))
- Refactor modified PodSpec to PodSpecMod [\#118](https://github.com/kedgeproject/kedge/pull/118) ([containscafeine](https://github.com/containscafeine))
- remove unused function isAnyConfigMapRef [\#117](https://github.com/kedgeproject/kedge/pull/117) ([containscafeine](https://github.com/containscafeine))
- run unit test and other basic test in travis-ci [\#107](https://github.com/kedgeproject/kedge/pull/107) ([kadel](https://github.com/kadel))
- fix gofmt formating errors [\#106](https://github.com/kedgeproject/kedge/pull/106) ([kadel](https://github.com/kadel))
- Switch to NodePort in example [\#102](https://github.com/kedgeproject/kedge/pull/102) ([cdrage](https://github.com/cdrage))
- add util file to pkg/cmd, refactor deploy,generate [\#99](https://github.com/kedgeproject/kedge/pull/99) ([containscafeine](https://github.com/containscafeine))
- Fixing typos as per comments. [\#97](https://github.com/kedgeproject/kedge/pull/97) ([pradeepto](https://github.com/pradeepto))
- Fix title and bits of readme. [\#95](https://github.com/kedgeproject/kedge/pull/95) ([pradeepto](https://github.com/pradeepto))
- add license header to all the code files [\#92](https://github.com/kedgeproject/kedge/pull/92) ([surajssd](https://github.com/surajssd))
- kapp -\> kedge [\#90](https://github.com/kedgeproject/kedge/pull/90) ([cdrage](https://github.com/cdrage))
- single-file example to be testable make it nodeport [\#88](https://github.com/kedgeproject/kedge/pull/88) ([surajssd](https://github.com/surajssd))
- add support for defining multiple apps in one file [\#86](https://github.com/kedgeproject/kedge/pull/86) ([containscafeine](https://github.com/containscafeine))
- feat\(spec\): add envFrom support in containers [\#84](https://github.com/kedgeproject/kedge/pull/84) ([surajssd](https://github.com/surajssd))
- rename ingress to ingresses [\#82](https://github.com/kedgeproject/kedge/pull/82) ([surajssd](https://github.com/surajssd))
- Update update readme, add development, roadmap and contributing docs [\#79](https://github.com/kedgeproject/kedge/pull/79) ([cdrage](https://github.com/cdrage))
- Auto populating port names, if not specified [\#76](https://github.com/kedgeproject/kedge/pull/76) ([containscafeine](https://github.com/containscafeine))
- Adding Makefile and helper scripts for validating code - gofmt, vendor checks etc. [\#74](https://github.com/kedgeproject/kedge/pull/74) ([pradeepto](https://github.com/pradeepto))
- make configData as list [\#73](https://github.com/kedgeproject/kedge/pull/73) ([surajssd](https://github.com/surajssd))
- Deploy command [\#72](https://github.com/kedgeproject/kedge/pull/72) ([kadel](https://github.com/kadel))
- small imports reordering [\#71](https://github.com/kedgeproject/kedge/pull/71) ([kadel](https://github.com/kadel))
- rename convert command to generate [\#70](https://github.com/kedgeproject/kedge/pull/70) ([kadel](https://github.com/kadel))
- add license apache v2 [\#66](https://github.com/kedgeproject/kedge/pull/66) ([surajssd](https://github.com/surajssd))
- validate container names [\#48](https://github.com/kedgeproject/kedge/pull/48) ([surajssd](https://github.com/surajssd))
- update readme [\#42](https://github.com/kedgeproject/kedge/pull/42) ([surajssd](https://github.com/surajssd))
- Don't create pod Volume if there already is one with the same name [\#40](https://github.com/kedgeproject/kedge/pull/40) ([kadel](https://github.com/kadel))
- populate name if one service specified, add tests [\#37](https://github.com/kedgeproject/kedge/pull/37) ([containscafeine](https://github.com/containscafeine))
- merge DeploymentSpec with PodSpec on the top level [\#36](https://github.com/kedgeproject/kedge/pull/36) ([kadel](https://github.com/kadel))
- implement ingress and ServiceSpec.Ports\[\].Endpoint [\#31](https://github.com/kedgeproject/kedge/pull/31) ([containscafeine](https://github.com/containscafeine))
- Minor changes to README [\#30](https://github.com/kedgeproject/kedge/pull/30) ([cdrage](https://github.com/cdrage))
- Rename OpenComposition to Kapp [\#29](https://github.com/kedgeproject/kedge/pull/29) ([cdrage](https://github.com/cdrage))
- Add health field to the container [\#27](https://github.com/kedgeproject/kedge/pull/27) ([surajssd](https://github.com/surajssd))
- refactor code [\#26](https://github.com/kedgeproject/kedge/pull/26) ([containscafeine](https://github.com/containscafeine))
- add root level persistent volume as pvc [\#25](https://github.com/kedgeproject/kedge/pull/25) ([surajssd](https://github.com/surajssd))
- Remove root level expose field [\#21](https://github.com/kedgeproject/kedge/pull/21) ([surajssd](https://github.com/surajssd))
- add file reference doc [\#20](https://github.com/kedgeproject/kedge/pull/20) ([surajssd](https://github.com/surajssd))
- vendor the logrus package [\#8](https://github.com/kedgeproject/kedge/pull/8) ([containscafeine](https://github.com/containscafeine))
- fix the way configmap literal is defined [\#7](https://github.com/kedgeproject/kedge/pull/7) ([surajssd](https://github.com/surajssd))
- Update install link [\#6](https://github.com/kedgeproject/kedge/pull/6) ([cdrage](https://github.com/cdrage))
- Add constants for volume sizes [\#5](https://github.com/kedgeproject/kedge/pull/5) ([cdrage](https://github.com/cdrage))
- Add .gitignore [\#4](https://github.com/kedgeproject/kedge/pull/4) ([cdrage](https://github.com/cdrage))
- Refactor CMD to reflect cobra defaults [\#3](https://github.com/kedgeproject/kedge/pull/3) ([cdrage](https://github.com/cdrage))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*