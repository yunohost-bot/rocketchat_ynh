<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Rocket.Chat for YunoHost

[![Integration level](https://dash.yunohost.org/integration/rocketchat.svg)](https://dash.yunohost.org/appci/app/rocketchat) ![Working status](https://ci-apps.yunohost.org/ci/badges/rocketchat.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/rocketchat.maintain.svg)  
[![Install Rocket.Chat with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=rocketchat)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Rocket.Chat quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Rocket.Chat is an open-source fully customizable communications platform developed in JavaScript for organizations with high standards of data protection.

### Features

- End to End Encryption
- LDAP/Active Directory
- Multifactor Authentication
- Customizable User Permission
- Mobile Apps for [iOS](https://apps.apple.com/app/rocket-chat/id1148741252) and [Android](https://play.google.com/store/apps/details?id=chat.rocket.android)
- Desktop Apps for [macOS](https://apps.apple.com/br/app/rocket-chat/id1086818840), [Linux](https://snapcraft.io/rocketchat-desktop) and [Windows](https://releases.rocket.chat/desktop/latest/download)

**Shipped version:** 4.8.1~ynh1

**Demo:** https://cloud.rocket.chat/trial

## Screenshots

![Screenshot of Rocket.Chat](./doc/screenshots/screenshot.jpg)

## Disclaimers / important information

### E-mail Configuration

To enable E-mail for address verification, go to Rocket.Chat Administration panel under E-mail -> SMTP and set as follow:

- Protocole: `smtp`
- Host: `localhost`
- Port: `25`
- From -mail: `rocketchat@domain.tld`

### Configure and activate federation for Rocket.Chat

https://support.indie.host/help/fr-fr/13/40

## Documentation and resources

* Official app website: <https://rocket.chat/>
* Official user documentation: <https://docs.rocket.chat/guides/user-guides>
* Official admin documentation: <https://docs.rocket.chat/>
* Upstream app code repository: <https://github.com/RocketChat/Rocket.Chat>
* YunoHost documentation for this app: <https://yunohost.org/app_rocketchat>
* Report a bug: <https://github.com/YunoHost-Apps/rocketchat_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/rocketchat_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/rocketchat_ynh/tree/testing --debug
or
sudo yunohost app upgrade rocketchat -u https://github.com/YunoHost-Apps/rocketchat_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
