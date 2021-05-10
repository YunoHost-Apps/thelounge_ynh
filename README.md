# The Lounge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/thelounge.svg)](https://dash.yunohost.org/appci/app/thelounge) ![](https://ci-apps.yunohost.org/ci/badges/thelounge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/thelounge.maintain.svg)  
[![Install The Lounge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=thelounge)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install The Lounge quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

The Lounge is a self-hosted IRC client.

**Shipped version:** 4.2.0

## Screenshots

![](https://raw.githubusercontent.com/thelounge/thelounge.github.io/master/img/thelounge-screenshot.png)

## Demo

* [Official demo](https://demo.thelounge.chat/)

## Configuration

How to configure this app: by an admin panel.

## Documentation

 * Official documentation: https://thelounge.chat/docs
 * YunoHost documentation: https://yunohost.org/en/app_thelounge

## YunoHost specific features

#### Multi-users support

* Are LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/thelounge.svg)](https://ci-apps.yunohost.org/ci/apps/thelounge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/thelounge.svg)](https://ci-apps-arm.yunohost.org/ci/apps/thelounge/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/thelounge_ynh/issues
 * App website: https://thelounge.chat/
 * Upstream app repository: https://github.com/thelounge/thelounge
 * YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
or
sudo yunohost app upgrade thelounge -u https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
```
