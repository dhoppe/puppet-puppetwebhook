# Changelog

All notable changes to this project will be documented in this file.
Each new release typically also includes the latest modulesync defaults.
These should not affect the functionality of the module.

## [v2.1.0](https://github.com/voxpupuli/puppet-puppetwebhook/tree/v2.1.0) (2021-04-28)

[Full Changelog](https://github.com/voxpupuli/puppet-puppetwebhook/compare/v2.0.0...v2.1.0)

**Implemented enhancements:**

- puppet/redis: Allow 7.x [\#42](https://github.com/voxpupuli/puppet-puppetwebhook/pull/42) ([bastelfreak](https://github.com/bastelfreak))
- puppetlabs/stdlib: Allow 7.x [\#41](https://github.com/voxpupuli/puppet-puppetwebhook/pull/41) ([bastelfreak](https://github.com/bastelfreak))
- camptocamp/systemd: allow 3.x [\#40](https://github.com/voxpupuli/puppet-puppetwebhook/pull/40) ([bastelfreak](https://github.com/bastelfreak))

## [v2.0.0](https://github.com/voxpupuli/puppet-puppetwebhook/tree/v2.0.0) (2021-03-11)

[Full Changelog](https://github.com/voxpupuli/puppet-puppetwebhook/compare/v1.2.0...v2.0.0)

**Breaking changes:**

- support puppet-webhook v2, drop V1 support [\#25](https://github.com/voxpupuli/puppet-puppetwebhook/pull/25) ([bastelfreak](https://github.com/bastelfreak))

**Implemented enhancements:**

- Enable Debian 10 support [\#37](https://github.com/voxpupuli/puppet-puppetwebhook/pull/37) ([bastelfreak](https://github.com/bastelfreak))
- Enable Ubuntu 20.04 support [\#36](https://github.com/voxpupuli/puppet-puppetwebhook/pull/36) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- clean up README.md [\#38](https://github.com/voxpupuli/puppet-puppetwebhook/pull/38) ([bastelfreak](https://github.com/bastelfreak))
- Enable Puppet 7 support [\#35](https://github.com/voxpupuli/puppet-puppetwebhook/pull/35) ([bastelfreak](https://github.com/bastelfreak))
- fix puppet-strings documentation [\#34](https://github.com/voxpupuli/puppet-puppetwebhook/pull/34) ([bastelfreak](https://github.com/bastelfreak))
- Create LICENSE [\#22](https://github.com/voxpupuli/puppet-puppetwebhook/pull/22) ([dhollinger](https://github.com/dhollinger))
- Add project\_page and issues\_url so PuppetForge generates links to GitHub [\#21](https://github.com/voxpupuli/puppet-puppetwebhook/pull/21) ([sgnl05](https://github.com/sgnl05))
- Allow `puppetlabs/stdlib` 6.x [\#20](https://github.com/voxpupuli/puppet-puppetwebhook/pull/20) ([alexjfisher](https://github.com/alexjfisher))

## [v1.2.0](https://github.com/voxpupuli/puppet-puppetwebhook/tree/v1.2.0) (2019-03-04)

[Full Changelog](https://github.com/voxpupuli/puppet-puppetwebhook/compare/v1.1.0...v1.2.0)

**Implemented enhancements:**

- Add `pkg_version` parameter [\#16](https://github.com/voxpupuli/puppet-puppetwebhook/pull/16) ([alexjfisher](https://github.com/alexjfisher))

**Fixed bugs:**

- Default for `command_prefix` is broken [\#15](https://github.com/voxpupuli/puppet-puppetwebhook/issues/15)
- Remove broken default `command_prefix` [\#18](https://github.com/voxpupuli/puppet-puppetwebhook/pull/18) ([alexjfisher](https://github.com/alexjfisher))
- Fix service not restarting on package update [\#17](https://github.com/voxpupuli/puppet-puppetwebhook/pull/17) ([alexjfisher](https://github.com/alexjfisher))

**Merged pull requests:**

- Fix `source` in metadata.json [\#13](https://github.com/voxpupuli/puppet-puppetwebhook/pull/13) ([alexjfisher](https://github.com/alexjfisher))

## [v1.1.0](https://github.com/voxpupuli/puppet-puppetwebhook/tree/v1.1.0) (2019-01-17)

[Full Changelog](https://github.com/voxpupuli/puppet-puppetwebhook/compare/v1.0.0...v1.1.0)

**Fixed bugs:**

- Ensure appropriate ENV file exists for setting puppet\_webhook service ENV Vars [\#11](https://github.com/voxpupuli/puppet-puppetwebhook/pull/11) ([dhollinger](https://github.com/dhollinger))

**Closed issues:**

- puppet\_webhook does not start [\#10](https://github.com/voxpupuli/puppet-puppetwebhook/issues/10)

## [v1.0.0](https://github.com/voxpupuli/puppet-puppetwebhook/tree/v1.0.0) (2018-11-13)

[Full Changelog](https://github.com/voxpupuli/puppet-puppetwebhook/compare/b89a1244b8fc404fb851dd34779785ff653be861...v1.0.0)

**Implemented enhancements:**

- Add acceptance tests [\#8](https://github.com/voxpupuli/puppet-puppetwebhook/pull/8) ([dhollinger](https://github.com/dhollinger))
- Fix permissions for the config file/directories and clean up tests [\#7](https://github.com/voxpupuli/puppet-puppetwebhook/pull/7) ([dhollinger](https://github.com/dhollinger))
- initial README commit [\#6](https://github.com/voxpupuli/puppet-puppetwebhook/pull/6) ([dhollinger](https://github.com/dhollinger))
- Add service code [\#5](https://github.com/voxpupuli/puppet-puppetwebhook/pull/5) ([dhollinger](https://github.com/dhollinger))
- Add config class and some basic params. [\#4](https://github.com/voxpupuli/puppet-puppetwebhook/pull/4) ([dhollinger](https://github.com/dhollinger))
- Add data type for puppet\_webhook config [\#3](https://github.com/voxpupuli/puppet-puppetwebhook/pull/3) ([dhollinger](https://github.com/dhollinger))
- Create install class and unit tests [\#2](https://github.com/voxpupuli/puppet-puppetwebhook/pull/2) ([dhollinger](https://github.com/dhollinger))
- Add sync yml [\#1](https://github.com/voxpupuli/puppet-puppetwebhook/pull/1) ([dhollinger](https://github.com/dhollinger))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
