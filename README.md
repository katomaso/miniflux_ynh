# Miniflux RSS reader for YunoHost

[![Integration level](https://dash.yunohost.org/integration/miniflux.svg)](https://dash.yunohost.org/appci/app/miniflux) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.maintain.svg)  
[![Install Custom Webapp with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=miniflux)

## Overview

Miniflux RSS reader is a simple and powerful client for reading news from multiple sources. It is a Golang appication backed by PostgreSQL database. It supports multiple users, currently without support for LDAP
users and yunohost's SSO.

**Shipped version:** 2.4

## Screenshots

## Demo

## Configuration

## Documentation

## YunoHost specific features

#### Multi-users support

Yes, but not linked to yunohost users.

#### Supported architectures

**Currently only amd64 is supported!**

## Limitations

## Additional information

## Links

 * Report a bug: https://github.com/YunoHost-Apps/my_webapp_ynh/issues
 * YunoHost website: https://yunohost.org/
 * Miniflux https://miniflux.app/


Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing --debug
or
sudo yunohost app upgrade my_webapp -u https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing --debug
```
