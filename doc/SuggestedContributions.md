SUGGESTED CONTRIBUTIONS
=======================
Thank you for your interest in participating in our community and helping us achieve our vision to produce open source software designed to reduce storage costs and help the world save the Datasphere!

This file contains information about the different ways to contribute to the CORTX Community as well as a list of specific suggested contributions.

GENERAL WAYS TO CONTRIBUTE
--------------------------
There are many ways to participate in our community.
1. Produce new test results (e.g. compare performance when using HDD for metadata as opposed to SSD)
2. Find and report new bugs
3. Fix bugs
4. Ask and answer questions in our various discussion forums
5. Improve our documentation
6. Improve our code quality
7. Improve our automation, devops, and CI/CD
8. Add new features
9. Identify and document the need for new features  

Note that not all of these require actively committing new code or documentation to the repositories but in general we prefer that all of them do result in code or documentation commits.  For example, if you participate in an important QA session in one of our discussion forums, this suggests that our documentation is somewhere lacking.  Please take what you learn from that QA session and improve our documentation so that the next visitor to our community won't have the same question.

SPECIFIC SUGGESTED CONTRIBUTIONS
--------------------------------
Here is a list of our current ideas about useful specific contributions that you can make.  Some of them have the name of a CORTX Team member who can help with additional details.
* Improve the documentation 
* Fix bugs 
  * How can we share our bug backlog with innersource community? 
* FDMI extension 
  * Ganesan
* Stress testing 
* Performance testing of kvs 
  * John Bent
* IOR integration with clovis 
  * John Bent
* Fio with clovis 
* Use of locks with clovis 
* Performance impact of lock usage 
* Test complete path with net socket transport 
* Stabilization of net socket transport 
* Performance with net socket transport 
* S3server/scripts/env/dev/init.sh 
  * [DEPRECATION WARNING]: Invoking "yum" only once while using a loop via squash_actions is deprecated. Instead of using a loop to supply multiple items and specifying `pkg: "{{item}}"`, please use `pkg: ['openldap-servers', 'openldap-clients']` and remove the loop. This feature will be removed in version 2.11. Deprecation warnings can be disabled by setting deprecation_warnings=False  in ansible.cfg. 
* dstat performance plugins 
  * Anatoliy
* Data-, metadata- path flows visualization tools. 
  * Anatoliy
* BErta(BE run time analysis) – metadata traversal python scripts used for debugging, visualization of metadata patterns and etc.
  * Anatoliy
* Make chronometry/addb tools to be useable for other people. Decreases slope of the Mero learning curve a lot. 
  * Anatoliy
* Chronometry/addb provements (at least Pearson Correlation) and Machine learning to identify abnormal behavior (for ex: some layouts may produce irregular network load pattern). 
  * Anatoliy
* FSCK for a single node. 
  * Anatoliy
* Expose low level block allocation algorithm interfaces and apply own allocation strategy. Will be useful for research, in production will hit “updates” case. 
  * Anatoliy
* Expose low level btree (KVS) interfaces. Will be useful for research, in production will hit “updates” case. 
  * Anatoliy
* System Performance model. 
  * Anatoliy
* System HA model. 
  * Anatoliy
* Simplify build process: install dependencies automatically 
  * Nikita
* Simplify deployment: run in a “demo” mode on a single node without root access and without real storage devices (files or loop devices) 
  * Nikita
* See doc/todo in the mero repository 
  * Nikita
* Convert existing project documentation into searcheable and versionable format and put it into the repositories 
* Get it working on Windows Subsystem Linux.  Add documentation and a downloadable VM image. 
* Improve CI/CD and other automated tasks.  When you do these, please document them in docs/CI_CD.md. 
* Add documentation for testing CORTX in a scale-out cluster. 
* Make it easier to build and test CORTX across a variety of kernel versions and Linux distributions and document this. 
* Replace LNet which requires kernel and results in many build dependencies and complexities with [DAOS Cart](https://github.com/daos-stack/cart) which runs in user-space
  * John Bent

