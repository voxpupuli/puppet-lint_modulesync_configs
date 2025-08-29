# Changelog

All notable changes to this project will be documented in this file.

## [2.0.0](https://github.com/voxpupuli/puppet-lint_modulesync_configs/tree/2.0.0) (2025-08-29)

[Full Changelog](https://github.com/voxpupuli/puppet-lint_modulesync_configs/compare/1.0.1...2.0.0)

**Merged pull requests:**

- manage puppet-lint-exec\_idempotency-check and order alphabetically [\#60](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/60) ([bastelfreak](https://github.com/bastelfreak))
- Update modulesync requirement from ~\> 3.5 to ~\> 4.0 [\#59](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/59) ([dependabot[bot]](https://github.com/apps/dependabot))
- Cleanup CI configuration [\#58](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/58) ([bastelfreak](https://github.com/bastelfreak))
- CI: Add minimal permissions [\#57](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/57) ([bastelfreak](https://github.com/bastelfreak))
- Remove SimpleCov code as it gets done by PuppetLint [\#55](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/55) ([msalway](https://github.com/msalway))

## [1.0.1](https://github.com/voxpupuli/puppet-lint_modulesync_configs/tree/1.0.1) (2025-03-14)

[Full Changelog](https://github.com/voxpupuli/puppet-lint_modulesync_configs/compare/1.0.0...1.0.1)

## [1.0.0](https://github.com/voxpupuli/puppet-lint_modulesync_configs/tree/1.0.0) (2025-03-14)

[Full Changelog](https://github.com/voxpupuli/puppet-lint_modulesync_configs/compare/f48bd9d630f90ed98c68e26a2fa28d17d10503c7...1.0.0)

**Breaking changes:**

- lint plugins: Drop Ruby \< 2.7 support [\#41](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/41) ([bastelfreak](https://github.com/bastelfreak))
- Run rubocop on plugins in CI; use voxpupuli-rubocop [\#28](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/28) ([smortex](https://github.com/smortex))

**Implemented enhancements:**

- add puppet-lint-variable\_contains\_upcase [\#47](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/47) ([bastelfreak](https://github.com/bastelfreak))
- GHA: Add names to CI jobs [\#30](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/30) ([bastelfreak](https://github.com/bastelfreak))
- Implement codecov coverage reporting [\#20](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/20) ([bastelfreak](https://github.com/bastelfreak))
- Run tests + release on Ruby 3 [\#6](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/6) ([bastelfreak](https://github.com/bastelfreak))
- puppet-lint gems: Publish to GitHub packages as well [\#4](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/4) ([bastelfreak](https://github.com/bastelfreak))

**Fixed bugs:**

- Require rspec-collection\_matchers [\#54](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/54) ([paran1](https://github.com/paran1))
- release action: only run on new tags [\#17](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/17) ([bastelfreak](https://github.com/bastelfreak))
- fix bug in Gemfile [\#15](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/15) ([bastelfreak](https://github.com/bastelfreak))
- fix typo in release github action [\#14](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/14) ([bastelfreak](https://github.com/bastelfreak))
- Release job: ensure ~/.gem exists [\#11](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/11) ([bastelfreak](https://github.com/bastelfreak))
- fix modulesync config [\#5](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/5) ([bastelfreak](https://github.com/bastelfreak))

**Merged pull requests:**

- puppet-lint plugins: Update actions/checkout v3-\>v4 [\#53](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/53) ([bastelfreak](https://github.com/bastelfreak))
- Dont deploy dependabot for puppet-lint plugins [\#52](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/52) ([bastelfreak](https://github.com/bastelfreak))
- bump voxpupuli rubocop dependency to 2.0 [\#50](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/50) ([zilchms](https://github.com/zilchms))
- add puppet-ghostbuster to managed modules [\#49](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/49) ([zilchms](https://github.com/zilchms))
- Add puppet-lint-manifest\_whitespace-check [\#48](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/48) ([bastelfreak](https://github.com/bastelfreak))
- lint plugins: Enable Ruby 3.2 testing [\#46](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/46) ([bastelfreak](https://github.com/bastelfreak))
- list development deps in Gemfile [\#45](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/45) ([bastelfreak](https://github.com/bastelfreak))
- gem build: increase verbosity and strictness [\#44](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/44) ([bastelfreak](https://github.com/bastelfreak))
- release job: skip not required gems [\#43](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/43) ([bastelfreak](https://github.com/bastelfreak))
- GCG: Add missing faraday-retry dependency [\#42](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/42) ([bastelfreak](https://github.com/bastelfreak))
- dependabot: check for actions and gems [\#40](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/40) ([bastelfreak](https://github.com/bastelfreak))
- CI: Run on PRs and merges to master [\#39](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/39) ([bastelfreak](https://github.com/bastelfreak))
- Dependabot: Update GitHub actions and gems [\#38](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/38) ([bastelfreak](https://github.com/bastelfreak))
- Add puppet-lint-param-types [\#37](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/37) ([bastelfreak](https://github.com/bastelfreak))
- Deploy dependabot for puppet-lint plugins + puppet-lint\_modulesync\_configs [\#36](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/36) ([bastelfreak](https://github.com/bastelfreak))
- Add Ruby 3.1 to CI [\#35](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/35) ([bastelfreak](https://github.com/bastelfreak))
- Add `topscope-variable-check` [\#34](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/34) ([alexjfisher](https://github.com/alexjfisher))
- remove puppet-lint-classes\_and\_types\_beginning\_with\_digits-check [\#33](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/33) ([bastelfreak](https://github.com/bastelfreak))
- remove puppet-lint-empty\_string-check [\#32](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/32) ([bastelfreak](https://github.com/bastelfreak))
- add puppet-lint-params\_empty\_string-check [\#31](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/31) ([bastelfreak](https://github.com/bastelfreak))
- Add puppet-lint-lookup\_in\_parameter-check module [\#27](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/27) ([smortex](https://github.com/smortex))
- Skip installation of a bundle for releasing [\#26](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/26) ([smortex](https://github.com/smortex))
- Clean up GHA release workflow a bit [\#25](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/25) ([ekohl](https://github.com/ekohl))
- Add `puppet-lint-strict_indent-check` [\#24](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/24) ([alexjfisher](https://github.com/alexjfisher))
- CI: ensure gem can be built [\#22](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/22) ([bastelfreak](https://github.com/bastelfreak))
- Indent using regular spaces [\#21](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/21) ([smortex](https://github.com/smortex))
- Add puppet-lint-optional\_default-check [\#19](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/19) ([bastelfreak](https://github.com/bastelfreak))
- Add simplecov integration [\#16](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/16) ([alexjfisher](https://github.com/alexjfisher))
- Don't manage LICENSE in modules [\#13](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/13) ([bastelfreak](https://github.com/bastelfreak))
- Release action: limit to voxpupuli org [\#12](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/12) ([bastelfreak](https://github.com/bastelfreak))
- add github\_changelog\_generator to Gemfile skeleton [\#10](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/10) ([bastelfreak](https://github.com/bastelfreak))
- dont install release group in release workflow [\#9](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/9) ([bastelfreak](https://github.com/bastelfreak))
- dont install release gem group [\#8](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/8) ([bastelfreak](https://github.com/bastelfreak))
- Add vendor/bundle directories to .gitignore [\#7](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/7) ([bastelfreak](https://github.com/bastelfreak))
- puppet-lint gems: Ignore `.vendor` in .gitignore [\#3](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/3) ([bastelfreak](https://github.com/bastelfreak))
- Update base files [\#2](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/2) ([ekohl](https://github.com/ekohl))
- Revive repository and update configs [\#1](https://github.com/voxpupuli/puppet-lint_modulesync_configs/pull/1) ([ekohl](https://github.com/ekohl))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
