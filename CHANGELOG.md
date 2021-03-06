## 0.4.1 / 2014-02-13

### Bug fixes

* Up version tag in code for `dvm version`. (@fnichol)


## 0.4.0 / 2014-02-13

### New features

* Upgrade to [boot2docker 0.5.4](https://github.com/steeve/boot2docker/releases/tag/v0.5.4). ([@fnichol][])
* Support VirtualBox and VMware Fusion/Workstation, thanks to [@mitchellh][] upstream. ([@fnichol][])

### Improvements

* Pull request [#17][]: Install Vagrant and VirtualBox with homebrew-cask. ([@hiremaga][])
* Pull request [#11][]: Spelling updates in README. ([@agoddard][])
* Update inlined plugin code to not collide with Vagrant 1.5.0 support. ([@fnichol][])


## 0.3.0 / 2014-01-16

### New features

* Upgrade to [boot2docker 0.4.0](https://github.com/steeve/boot2docker/releases/tag/v0.4.0). ([@fnichol][])
* Issue [#5][]: Hombrew formula moved to a tap at [fnichol/hombrew-dvm](https://github.com/fnichol/homebrew-dvm). ([@jfoy][], [@fnichol][])

### Improvements

* Ensure that there is a sane DNS resolver on boot for docker daemon. ([@fnichol][])
* Use the host's resolver as a DNS proxy in NAT mode. ([@fnichol][])
* Pull request [#6][]: Add support for fish shell. ([@tlockney][])
* Pull request [#3][]: Update Mac/Docker documentation. ([@gianpaj][])


## 0.2.2 / 2014-01-06

### Bug fixes

* Pull request [#2][]: Explicitly set the provider to virtualbox. ([@hmarr][])

### Improvements

* Pull request [#3][]: Update README since docker is now available via homebrew. ([@gianpaj][])


## 0.2.1 / 2014-01-06

### Improvements

* Update to boot2docker-vagrant-box 0.3.0-1 which sets `shell = "sh -l"`. ([@fnichol][])
* Add `dvm help` subcommand, in addition to `--help` and `-h` flags. ([@fnichol][])


## 0.2.0 / 2014-01-05

### Changes

* Overwrite Vagrantfile on `make install`. ([@fnichol][])

### New features

* Use a Vagrant private network to communicate with Docker VM. ([@fnichol][])
* Add `dvm reload` subcommand. ([@fnichol][])


## 0.1.0 / 2014-01-05

The initial release.

<!--- The following link definition list is generated by PimpMyChangelog --->
[#2]: https://github.com/fnichol/dvm/issues/2
[#3]: https://github.com/fnichol/dvm/issues/3
[#5]: https://github.com/fnichol/dvm/issues/5
[#6]: https://github.com/fnichol/dvm/issues/6
[#11]: https://github.com/fnichol/dvm/issues/11
[#17]: https://github.com/fnichol/dvm/issues/17
[@agoddard]: https://github.com/agoddard
[@fnichol]: https://github.com/fnichol
[@gianpaj]: https://github.com/gianpaj
[@hiremaga]: https://github.com/hiremaga
[@hmarr]: https://github.com/hmarr
[@jfoy]: https://github.com/jfoy
[@mitchellh]: https://github.com/mitchellh
[@tlockney]: https://github.com/tlockney
