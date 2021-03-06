rs-haproxy Cookbook CHANGELOG
=======================

This file is used to list changes made in each version of the rs-haproxy cookbook.

v1.1.3
------

- Fix issue with backend servers not being monitored [#25][]
- Added config option to disable support for SSLv3.
- Update the default HAProxy source version to 1.5.6.

v1.1.2
------

- Add testing for support of Ubuntu 14.04, CentOS 7.0, and RedHat Enterprise Linux 7.0.
- Update the default HAProxy source version to 1.5.4.

v1.1.1
------

- Enable/disable schedule to periodically run rs-haproxy::frontend.

v1.1.0
------

- Installs HAProxy 1.5.1
- Created `rs-haproxy::schedule` recipe
- HAProxy logs via rsyslog to `/var/log/haproxy.log`
- HAProxy version determined by name of source file
- In `rs-haproxy::frontend`, if no application servers are discovered, do nothing
- Created rspec tests for `rs-haproxy::schedule`

v1.0.0
------

- Initial release

<!--- The following link definition list is generated by PimpMyChangelog --->
[#25]: https://github.com/rightscale-cookbooks/rs-haproxy/issues/25