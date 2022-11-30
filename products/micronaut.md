---
title: Micronaut Framework
category: framework
iconSlug: NA
permalink: /micronaut
alternate_urls:
-   /micronaut-framework
releasePolicyLink: https://micronaut.io/support-schedule/
changelogTemplate: "https://github.com/micronaut-projects/micronaut-core/releases/tag/v__LATEST__"
activeSupportColumn: true
releaseColumn: true
releaseDateColumn: true

auto:
-   git: https://github.com/micronaut-projects/micronaut-core.git
# See https://rubular.com/r/8pbKdwLoxZjyt4 for reference
    regex: '^v?(?<major>[1-9]\d*)\.(?<minor>0|[1-9]\d*)\.(?<patch>0|[1-9]\d*)$'

releases:
- releaseCycle: "3"
  releaseDate: 2021-08-18
  eol: false
  support: true
  latest: "3.7.4"
  latestReleaseDate: 2022-11-16

- releaseCycle: "2"
  releaseDate: 2020-06-26
  eol: false
  support: false
  latest: "2.5.13"
  latestReleaseDate: 2021-09-03

- releaseCycle: "1"
  releaseDate: 2018-10-23
  eol: 2021-12-31
  support: false
  latest: "1.3.7"
  latestReleaseDate: 2020-07-10

---

> [Micronaut](https://quarkus.io/) is a modern, JVM-based, full-stack framework for building modular, easily testable
> microservice and serverless applications.

Versions of the Micronaut framework may fall into one of three lifecycle stages:

- Active Development: those versions receive regular updates.
- Active Maintenance: those versions receive limited bug fixes and patches, mostly focused around the resolution of critical security advisories.
- End of Support: those versions reached End-Of-Life.

The Micronaut Foundation offers [commercial support](https://micronaut.io/support/) for those who want extended support.
