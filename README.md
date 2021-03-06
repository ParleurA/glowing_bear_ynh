# Glowing Bear for YunoHost

[![Integration level](https://dash.yunohost.org/integration/glowingbear.svg)](https://dash.yunohost.org/appci/app/glowingbear)
[![Install glowingbear with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=glowingbear)

> *This package allow you to install glowingbear quickly and simply on a YunoHost server.

If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Glowing Bear is a web frontend for the WeeChat IRC client and strives to be a modern interface. It relies on WeeChat to do all the heavy lifting and then provides some nice features on top of that, like embedding images, videos, and other content. The best part, however, is that you can use it from any modern internet device -- whether it's a computer, tablet, or smart phone -- and all your stuff is there, wherever you are. You don't have to deal with the messy technical details, and all you need to have installed is a browser or our app.

**Shipped version:** 0.8.0

## Screenshots

![](https://camo.githubusercontent.com/277788ad057cf6934499621c7ba1193e6edbdb0e/68747470733a2f2f347a322e64652f676c6f77696e67626561722e706e67)

## Demo

* None.

## Configuration

* You should run `apt install weechat` on your Yunohost installation
* Follow https://github.com/glowing-bear/glowing-bear#getting-started

## Documentation

 * Official documentation: https://github.com/glowing-bear/glowing-bear
 * YunoHost documentation: https://github.com/YunoHost-Apps/glowing_bear_ynh

## YunoHost specific features

#### Multi-users support

* Is LDAP supported? No, not relevant.
* Is HTTP auth supported? Yes.
* Can the app be used by multiple users? No.

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/glowingbear%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/glowingbear/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/glowingbear%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/glowingbear/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/glowingbear%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/glowingbear/)

## Limitations

None so far.

## Additional information

None.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/glowingbear_ynh/issues
 * App website: https://www.glowing-bear.org/
 * Upstream app repository: https://github.com/glowing-bear/glowing-bear
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/glowingbear_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/glowingbear_ynh/tree/testing --debug
or
sudo yunohost app upgrade glowingbear -u https://github.com/YunoHost-Apps/glowingbear_ynh/tree/testing --debug
```
