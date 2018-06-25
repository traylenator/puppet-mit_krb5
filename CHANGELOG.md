#### 2018-06-25 - Remi Ferrand <puppet@cc.in2p3.fr> - 0.4.1

* Migrate to PDK version `1.6.0`
* Introduce new dependency on `ccin2p3-etc_services`

##### Fixes
* Fixes `metadata.json` (See [#10](https://github.com/ccin2p3/puppet-mit_krb5/pull/10))

##### New features
* Add support for options `default_ccache_name` and `pkinit_anchors` (See [#11](https://github.com/ccin2p3/puppet-mit_krb5/pull/11))
* Add support for option ̀`canonicalize` (See [#7](https://github.com/ccin2p3/puppet-mit_krb5/pull/7))

#### 2016-03-31 - Fabien Wernli <puppet@cc.in2p3.fr> - 0.2.1

* add compatibility with concat 2.x

#### 2014-10-31 - Remi Ferrand <puppet@cc.in2p3.fr> - 0.1.0
##### History
This Puppet module was originaly created by Patrick Mooney (https://github.com/pfmooney/puppet-mit_krb5). The module was forked by CC-IN2P3 because P. Mooney couldn't provide active support anylonger.
##### New features
* Add `appdefaults` section (https://github.com/pfmooney/puppet-mit_krb5/pull/3)
* Add `v4_name_convert` and `kpasswd_server` support in _[realm]_ section (https://github.com/pfmooney/puppet-mit_krb5/pull/3)
