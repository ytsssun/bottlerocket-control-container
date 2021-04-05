# 0.5.0

* Add support for on-premises and hybrid environments. ([#12])
* Symlinked `/var/lib/amazon/ssm` to `/.bottlerocket/host-containers/current/ssm` so that SSM Agent state data can persist between boots. ([#12])
* Update SSM Agent version to 3.0.882.0. ([#12])

[#12]: https://github.com/bottlerocket-os/bottlerocket-control-container/pull/12

# 0.4.2

* Update SSM Agent version to 3.0.732.0. ([#8])

[#8]: https://github.com/bottlerocket-os/bottlerocket-control-container/pull/8

# 0.4.1

* Update SSM Agent version to 2.3.1569.0. ([#5])

[#5]: https://github.com/bottlerocket-os/bottlerocket-control-container/pull/5

# 0.4.0

Initial release of **bottlerocket-control-container** - the default control container for Bottlerocket.

See the [README](README.md) for additional information.
