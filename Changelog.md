# Changelog

**latest**
- shallow clone gitlab-ci-runner
- update to sameersbn/ubuntu:14.04.20140628 base image
- removed sshd start, use nsenter instead

**5.0.0**
- upgrade to gitlab-ci-runner 5.0.0
- upgrade to sameersbn/ubuntu:14.04.20140505 base image
- added CA_CERTIFICATES_PATH configuration option
- use sameersbn/ubuntu as the base docker image
- install ruby2.0 via ppa

**4.0.0**
 - initial creation, adapted from https://github.com/sameersbn/docker-gitlab-ci
