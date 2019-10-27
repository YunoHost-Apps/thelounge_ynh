# The Lounge for YunoHost

[![Integration level](https://dash.yunohost.org/integration/thelounge.svg)](https://dash.yunohost.org/appci/app/thelounge)

[![Install The Lounge with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=thelounge)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install The Lounge quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

- **Modern features brought to IRC.** Push notifications, link previews, new message markers, and more bring IRC to the 21st century.
- **Always connected.** Remains connected to IRC servers while you are offline.
- **Cross platform.** It doesn't matter what OS you use, it just works wherever Node.js runs.
- **Responsive interface.** The client works smoothly on every desktop, smartphone and tablet.
- **Synchronized experience.** Always resume where you left off no matter what device.

**Shipped version:** 3.2.0

## Screenshots

![](https://raw.githubusercontent.com/thelounge/thelounge.github.io/master/img/thelounge-screenshot.png)

## Demo

* [Official demo](https://demo.thelounge.chat/)

## Configuration

How to configure this app: by an admin panel

## Documentation

 * Official documentation: https://thelounge.chat/docs
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

LDAP is supported

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/thelounge%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/thelounge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/thelounge%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/thelounge/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/thelounge%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/thelounge/)

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/thelounge_ynh/issues
 * App website: https://thelounge.chat/
 * Upstream app repository: https://github.com/thelounge/thelounge
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
or
sudo yunohost app upgrade thelounge -u https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
```