Jenkins Claim Plugin
=========================

A plugin for Jenkins CI that allows users to claim (take responsibility) for a failing build or assign it to another user (aka blame).<br>
Look at [wiki] for detailed instructions.

Change Log
----------
### v2.9 (14 Nov 2016)
- Fixed single quote failure introduced in 2.8 [JENKINS-28722]
- Removed unused json2.js [JENKINS-33078]
- Fix Class Cast Exception when claiming test [JENKINS-33715]
- Support new version of build failure plugin
- "Claim it" link for tests didn't work when BFA plugin isn't installed [JENKINS-39538]
- Claiming tests isn't compatible with Jenkins 2.0 pipelines [JENKINS-39537]

### v2.8 (14 Jan 2016)
- Integrate Build-Failure-Analyzer Plugin [JENKINS-28722]
- Add support for workflow (use SimpleBuildStep) [JENKINS-27206]

### v2.7 (12 May 2015)
- Fixed compatibility with Jenkins Core 1.577 and newer [JENKINS-27091]

### v2.6 (9 Mar 2015)
- Claim stickiness default value is now a globally configurable [JENKINS-27002]
- Added support for running a global groovy script whenever a claim is changed

### v2.5 (8 Dec 2014)
- You can now claim for other users than yourself [JENKINS-7824]

~~v2.4 (14 Oct 2014)~~

### v2.3 (18 Nov 2013)
- Add support for hierarchical projects [JENKINS-17734]

### v2.2 (27 Mar 2013)
- Added support for translations and added Chinese translation
- Added new icon to make claim plugin more visible
- All jobs are now visible in claim report [JENKINS-16801]

### v2.1 (12 Feb 2013)

- Fixed HTML rendering issue introduced in 2.0 [JENKINS-16766]

### v2.0 (6 Feb 2013)

- Store and display a date of when a claim was added.
- ~~Option to sticky claim test failures if the failure is "similiar"~~
- Improved Matrix claim information

### v1.7 (4 Maj 2010)

- Show user names in claims instead of ids.
- Support for claiming Matrix builds.

### v1.6 (28 Nov 2009)

- Updated claim plugin to match updated Jenkins API

### v1.5 (17 July 2011)

- Make sure that the claim plugin runs after all the other extensions that can change the build status run.

[JENKINS-39538]: https://issues.jenkins-ci.org/browse/JENKINS-39538
[JENKINS-39537]: https://issues.jenkins-ci.org/browse/JENKINS-39537
[JENKINS-33715]: https://issues.jenkins-ci.org/browse/JENKINS-33715
[JENKINS-33078]: https://issues.jenkins-ci.org/browse/JENKINS-33078
[JENKINS-28722]: https://issues.jenkins-ci.org/browse/JENKINS-28722
[JENKINS-27206]: https://issues.jenkins-ci.org/browse/JENKINS-27206
[JENKINS-27091]: https://issues.jenkins-ci.org/browse/JENKINS-27091
[JENKINS-27002]: https://issues.jenkins-ci.org/browse/JENKINS-27002
[JENKINS-17734]: https://issues.jenkins-ci.org/browse/JENKINS-17734
[JENKINS-16801]: https://issues.jenkins-ci.org/browse/JENKINS-16801
[JENKINS-16766]: https://issues.jenkins-ci.org/browse/JENKINS-16766
[JENKINS-7824]: https://issues.jenkins-ci.org/browse/JENKINS-7824
[wiki]: https://wiki.jenkins-ci.org/display/JENKINS/Claim+plugin