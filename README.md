<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ntfy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ntfy.svg)](https://dash.yunohost.org/appci/app/ntfy) ![Working status](https://ci-apps.yunohost.org/ci/badges/ntfy.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/ntfy.maintain.svg)  
[![Install ntfy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ntfy)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ntfy quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Open Source Push Notification Server

**Shipped version:** 1.29.0~ynh1

**Demo:** https://ntfy.sh/app
## Disclaimers / important information


### Configuration
By default, only user selected at installation can read from and write to topics. To change this refer to the upstream project's documentation: https://docs.ntfy.sh/config/#access-control

The configuration file is located at `/var/www/<app>/server.yml`.

### Limitations
- requires a dedicated (sub-)domain
- no LDAP support by upstream application


## Documentation and resources

* Official app website: <https://ntfy.sh/>
* Official user documentation: <https://docs.ntfy.sh/>
* Official admin documentation: <https://docs.ntfy.sh/>
* Upstream app code repository: <https://github.com/binwiederhier/ntfy>
* YunoHost documentation for this app: <https://yunohost.org/app_ntfy>
* Report a bug: <https://github.com/YunoHost-Apps/ntfy_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ntfy_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/ntfy_ynh/tree/testing --debug
or
sudo yunohost app upgrade ntfy -u https://github.com/YunoHost-Apps/ntfy_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>