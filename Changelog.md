# Changelog

## 3.3.1

* `bump:*` runs twice if task is defined in `Rakefile`

## 3.3.0

* Allow releasing without building nor pushing to the forge, just git tagging [:clean, :tag, :bump_commit], using `build = false`

## 3.2.0

* Enable bumping semantic version elements with `module:bump:` plus `patch`, `minor`, `major`

## 3.1.0

* Added feature to bump dependencies `module:dependency[modulename, version]`
* Add support for custom tag patterns

## 3.0.3

* [Issue #11](https://github.com/maestrodev/puppet-blacksmith/issues/11) Require json and yaml in forge.rb
* [Issue #10](https://github.com/maestrodev/puppet-blacksmith/issues/10) Added support to git commit the version

## 3.0.2

* [Issue #9](https://github.com/maestrodev/puppet-blacksmith/issues/9) Better error messages when pushing to the Forge fails

## 3.0.1

* Fix uninitialized constant Blacksmith::VERSION

## 3.0.0

* Use API to upload to the Forge instead of parsing the webpage
* Use a custom Blacksmith `User-Agent`

## 2.3.1

* [Issue #7](https://github.com/maestrodev/puppet-blacksmith/issues/7) `module:bump_commit` fails if `Modulefile` does not exist

## 2.2.0

* [Issue #6](https://github.com/maestrodev/puppet-blacksmith/issues/6) Add support for `metadata.json`

## 2.1.0

* Support Puppet 3.5+

## 2.0.0

* Reworked to be a library plus rake tasks so it an be reused
* `.puppetforge.yml` `forge` entry is deprecated, use `url`
