<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Wiki.js for YunoHost

[![Integration level](https://dash.yunohost.org/integration/wikijs.svg)](https://dash.yunohost.org/appci/app/wikijs) ![](https://ci-apps.yunohost.org/ci/badges/wikijs.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/wikijs.maintain.svg)  
[![Install Wiki.js with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=wikijs)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Wiki.js quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Wiki.js is a copylefted libre software, modern and powerful wiki app built on Node.js, Git and Markdown for YunoHost.


**Shipped version:** 2.5.274~ynh1

**Demo:** https://docs-beta.requarks.io/

## Screenshots

![](./doc/screenshots/screenshot2.png)
![](./doc/screenshots/screenshot1.png)

## Disclaimers / important information

* **Wiki.js** requires a dedicated **root domain**, e.g. wikijs.domain.tld
* LDAP is implemented, root will receive an e-mail at the end of the installation or the upgrade with the info on how to configure LDAP.
* No HTTP auth for now, but planned for the future.

## Documentation and resources

* Official app website: https://wiki.js.org/
* Official user documentation: https://docs-beta.requarks.io/
* Official admin documentation: https://yunohost.org/en/app_wikijs
* Upstream app code repository: https://github.com/Requarks/wiki
* YunoHost documentation for this app: https://yunohost.org/app_wikijs
* Report a bug: https://github.com/YunoHost-Apps/wikijs_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
or
sudo yunohost app upgrade wikijs -u https://github.com/YunoHost-Apps/wikijs_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps