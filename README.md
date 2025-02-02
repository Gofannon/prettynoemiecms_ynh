# PrettyNoemieCMS for YunoHost

[![Integration level](https://dash.yunohost.org/integration/prettynoemiecms.svg)](https://dash.yunohost.org/appci/app/prettynoemiecms)  
[![Install prettynoemiecms with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=prettynoemiecms)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install prettynoemiecms quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
CMS offers its users an ergonomic solution, simple and elegant to build in no time responsive windows sites with modern design.
The construction of your site will consist of arranging at your convenience various modules, edit their content, and customize your site by choosing fonts, formatting text, and display colors.

**Shipped version:** 2019.05.23

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

Are LDAP and HTTP auth supported? **NO**  
Can the app be used by multiple users? **NO**

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/prettynoemiecms%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/prettynoemiecms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/prettynoemiecms%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/prettynoemiecms/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/prettynoemiecms%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/prettynoemiecms/)

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/prettynoemiecms_ynh/issues
 * App website: https://framagit.org/framasoft/PrettyNoemieCMS
 * Upstream app repository: https://framagit.org/framasoft/PrettyNoemieCMS
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
or
sudo yunohost app upgrade prettynoemiecms -u https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
```
