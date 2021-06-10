# PrettyNoemieCMS for YunoHost

[![Integration level](https://dash.yunohost.org/integration/prettynoemiecms.svg)](https://dash.yunohost.org/appci/app/prettynoemiecms) ![](https://ci-apps.yunohost.org/ci/badges/prettynoemiecms.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prettynoemiecms.maintain.svg)  
[![Install PrettyNoemieCMS with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prettynoemiecms)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install PrettyNoemieCMS quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/install) to know how to install and enjoy it.*

## Overview
PrettyNoemieCMS offers its users an ergonomic solution, simple and elegant to build in no time responsive windows sites with modern design.
The construction of your site will consist of arranging at your convenience various modules, edit their content, and customize your site by choosing fonts, formatting text, and display colors.

**Shipped version:** 2020.01.07

## Screenshots

![](https://framablog.org/wp-content/uploads/2018/02/pages-framasite-theme-light.gif)

## Demo

* [Official demo](https://demo-pretty-noemie.frama.site)

Login with:

    login : pretty
    mdp : 12345678


## Configuration

How to configure this app: by an admin panel at: `your.domain.tld/your_path/admin`

## Documentation

 * Official documentation: https://framagit.org/framasoft/PrettyNoemieCMS

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported? **No**  
Can the app be used by multiple users? **No**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/prettynoemiecms.svg)](https://ci-apps.yunohost.org/ci/apps/prettynoemiecms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/prettynoemiecms.svg)](https://ci-apps-arm.yunohost.org/ci/apps/prettynoemiecms/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/prettynoemiecms_ynh/issues
 * App website: https://framagit.org/framasoft/PrettyNoemieCMS
 * Upstream app repository: https://framagit.org/framasoft/PrettyNoemieCMS
 * YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
or
sudo yunohost app upgrade prettynoemiecms -u https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
```
