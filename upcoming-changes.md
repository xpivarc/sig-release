---
title: Noteworthy changes for the next KubeVirt release
---

# Noteworthy changes for the next KubeVirt release

This list contains the noteworthy changes made after the latest KubeVirt release. The community expects these changes to be included in the next Kubevirt release.

> [!WARNING]
> **Please be aware that any of these might be excluded from the next release.**

| Upcoming changes | PR                                                                   | Author                                          |
|------------------|----------------------------------------------------------------------|-------------------------------------------------|
| virtctl: It is possible to import volumes from GCS when creating a VM now  | [#11149](https://github.com/kubevirt/kubevirt/pull/11149) | [0xFelix](https://github.com/0xFelix) |
| KubeVirtComponentExceedsRequestedCPU and KubeVirtComponentExceedsRequestedMemory alerts are deprecated; they do not indicate a genuine issue.  | [#11404](https://github.com/kubevirt/kubevirt/pull/11404) | [avlitman](https://github.com/avlitman) |
| add cloudraft to adopters.  | [#11331](https://github.com/kubevirt/kubevirt/pull/11331) | [anjuls](https://github.com/anjuls) |
| add perf-scale benchmarks for release v1.2  | [#11387](https://github.com/kubevirt/kubevirt/pull/11387) | [alaypatel07](https://github.com/alaypatel07) |
| Expose volumesnapshot error in vmsnapshot object  | [#11095](https://github.com/kubevirt/kubevirt/pull/11095) | [ShellyKa13](https://github.com/ShellyKa13) |
| Bug-fix: Fix nil panic if VM update fails  | [#11372](https://github.com/kubevirt/kubevirt/pull/11372) | [xpivarc](https://github.com/xpivarc) |
| BugFix: Ensure DataVolumes created by virt-controller (DataVolumeTemplates) are recreated and owned by the VM in the case of DR and backup/restore.  | [#11267](https://github.com/kubevirt/kubevirt/pull/11267) | [mhenriks](https://github.com/mhenriks) |
| BugFix: Fixed incorrect APIVersion of APIResourceList  | [#10900](https://github.com/kubevirt/kubevirt/pull/10900) | [KarstenB](https://github.com/KarstenB) |
| fix(ksm): set the `kubevirt.io/ksm-enabled` node label to true if the ksm is managed by KubeVirt, instead of reflect the actual ksm value.  | [#11306](https://github.com/kubevirt/kubevirt/pull/11306) | [fossedihelm](https://github.com/fossedihelm) |
| More information in the migration state of VMI / migration objects  | [#11330](https://github.com/kubevirt/kubevirt/pull/11330) | [jean-edouard](https://github.com/jean-edouard) |
| Fix perfscale buckets error  | [#11264](https://github.com/kubevirt/kubevirt/pull/11264) | [machadovilaca](https://github.com/machadovilaca) |
| Extend OWNERS for sig-buildsystem  | [#11183](https://github.com/kubevirt/kubevirt/pull/11183) | [dhiller](https://github.com/dhiller) |
| fix(vmclone): delete vmclone resource when the target vm is deleted  | [#11058](https://github.com/kubevirt/kubevirt/pull/11058) | [fossedihelm](https://github.com/fossedihelm) |
| Bug fix: VM controller doesn't corrupt its cache anymore  | [#11265](https://github.com/kubevirt/kubevirt/pull/11265) | [xpivarc](https://github.com/xpivarc) |
| Fix migration breaking in case the VM has an rng device after hotplugging a block volume on cgroupsv2  | [#11205](https://github.com/kubevirt/kubevirt/pull/11205) | [akalenyu](https://github.com/akalenyu) |
| Bugfix: Improve error reporting when fsfreeze fails  | [#11051](https://github.com/kubevirt/kubevirt/pull/11051) | [alromeros](https://github.com/alromeros) |
| Move some verification from the VMI create validation webhook to the CRD<br>The webhook will no longer return the following errors:<br>* "spec.accessCredentials list exceeds the 256 element limit in length"<br>* "spec.domain.devices.disks list exceeds the 256 element limit in length"<br>* "spec.domain.devices.interfaces list exceeds the 256 element limit in length"<br>* "spec.networks list exceeds the 256 element limit in length"<br>* "spec.volumes list exceeds the 256 element limit in length"  | [#11156](https://github.com/kubevirt/kubevirt/pull/11156) | [nunnatsa](https://github.com/nunnatsa) |
| node-labeller: Remove obsolete functionalities  | [#11146](https://github.com/kubevirt/kubevirt/pull/11146) | [RamLavi](https://github.com/RamLavi) |


_This page is updated daily._
