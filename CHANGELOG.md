# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/3.1.0...3.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`1fabc0c`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/1fabc0c7acca4704cc14062687c83302775c47da)

## [3.1.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`9c7c944`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/9c7c944d437b0bc38b6790b3da19404790ef0141)
- add oraclelinux10 support + lint and core fixes [`06556d6`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/06556d6a9a073c564109055aee99d0c4e93b6fef)

## [3.0.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/2.1.0...3.0.0) - 2025-10-29

### Commits

- remove debian10 support [`c2e61c2`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/c2e61c2832f8d9a9cc03025793752735dd7631ed)
- update core, molecule + gitlab-ci [`cfb9310`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/cfb93104989908e3f04bcbd82c7509d0d7ec4d6c)
- changes on molecule [`f205cf5`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/f205cf5c4dd29805ecaff8031c65b4d84ade2f96)
- fix lint [`c304b40`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/c304b40814bdd1b3305ea20800343909b6a3854e)
- fix molecule paralelism and little updates [`e2cb653`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/e2cb6535b2ed24d4325ea8521ca8d790f49532ef)

## [2.1.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/2.0.0...2.1.0) - 2025-01-16

### Commits

- add support for ubuntu24 [`11d9f2a`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/11d9f2a8aca33d9ab62409205db5ce7d20db274b)
- add version on molecule play image to maintain support on old release [`ee8ade9`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/ee8ade950e6063781e0b04ce4d669dbd4b3d6b75)
- remove support for debian10 / ubuntu18 / redhat8 [`495b5de`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/495b5dea5dcccc8775edae7b716ae09920046b92)
- add redhat 9 to default supported distrib [`6850560`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/6850560e219fef50e90cd32137a4835182c47483)
- remove redhat molecule checks [`727a87a`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/727a87a0f513c0dfb2f89722ec30409581adef6e)
- sort testing distrib to avoid random changes [`b1c567f`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/b1c567f2222378b06f7e4c5b9b498502e1df078b)
- update pre-commit and lint fix [`e292974`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/e292974e370c05fc500a25ba8883c7b4bbc2a4ed)
- remove support for rhel7 and docker dind on gitlab [`afd6ad5`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/afd6ad599e697b0c29e79fb522550d2c14750b65)
- remove lint from pipeline [`edb4ef2`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/edb4ef2aa16776229d9414ea876865480fb8bc71)
- remove pipelines tests, moved in precommits [`5769655`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/5769655359393cd910836a947e93472d7bd2a95a)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`d74a991`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/d74a9911ececc46d87d2c94b76886a56c9bcf1b3)
- update precommit [`461efb8`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/461efb8903dc83289aecf93a1b2317c3970b5b5c)
- update readme + precommit + include vars [`2264792`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/2264792f1539958be94fa82fd8923f84c4c6bfac)

## [1.1.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`9334fd2`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/9334fd29d74a849e2ed383c055d34864e559d86e)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/0.4.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`5a21047`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/5a2104719feb9b31900a8f28b591b92cbee518f5)
- add precommit for lint [`13b6aff`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/13b6affc26684ac916752a1b242d3b3aa685c395)
- fix checks [`7213c64`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/7213c647c8b6c5303156d428316a8ada1065ab9e)
- add new molecule all scenario [`7dcbf0c`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/7dcbf0c0846873faaf98e9fa3721dcd5428e90f8)
- split distro for molecule tests on ci [`5faba69`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/5faba697ebc584aec3003493a1e757ade4325162)
- fix molecule ora9 [`0b051b6`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/0b051b6a9d244d07a4e203249f6de0a7d771b8b0)
- add ora9 support [`4f207a5`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/4f207a57b43f1d09796abb39ea41d1c275b637a9)
- fix checks [`e086708`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/e086708109696e927268992b07948b33e45c3e98)
- fix clone pipeline [`3da8fe2`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/3da8fe2f3c5f38ef71b85579ba9d44a9c5d9c9b9)
- fix: molecule image and optimize scenario [`0270737`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/0270737856aff19604f797b1b51b8d68cd821b54)

## [0.4.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/0.3.0...0.4.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`7b57f05`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/7b57f0531caadaa9823ca55e8b3a7d3245abb998)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/0.2.0...0.3.0) - 2022-06-27

### Commits

- minor: add oracleLinux support + little fixes [`d968769`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/d968769a3e68799006c79089546c1f4901c51963)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/0.1.1...0.2.0) - 2022-06-07

### Commits

- fix: remove unsupported centos8 + minor fixes [`f40f6f6`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/f40f6f6656bcec3dbe7e4a171ff7a8eab72f3b20)
- fix: wrong .deb name for debian11 packages [`1db85d4`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/1db85d42edda2b2cffdba41e0fa33c2f91541740)
- fix: update freeipa package version for debian11 [`dc4462e`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/dc4462e0acead66a615ad8af79d8553bec42660f)

## [0.1.1](https://github.com/lotusnoir/ansible-apps_freeipa_client/compare/0.1.0...0.1.1) - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`72a36cf`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/72a36cf63a8e89b8ddc2f7aa2406a5464e9baf25)

## 0.1.0 - 2021-11-16

### Commits

- fix: add role name on molecule container names to avoid concurrent conflict on runners [`54c4b85`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/54c4b85e081b05381c3373a579b0650c00e31b5d)
- fix: can't run molecule test on pipleine [`186866a`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/186866aea39ef4018f108478273837e0a7dd9e71)
- fix molecule error [`9f8a426`](https://github.com/lotusnoir/ansible-apps_freeipa_client/commit/9f8a4266d11ea58fa98726cde871f7c448f17032)
