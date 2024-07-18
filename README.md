<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Roundcube for YunoHost

[![Integration level](https://dash.yunohost.org/integration/roundcube.svg)](https://ci-apps.yunohost.org/ci/apps/roundcube/) ![Working status](https://ci-apps.yunohost.org/ci/badges/roundcube.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/roundcube.maintain.svg)

[![Install Roundcube with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=roundcube)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Roundcube quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Roundcube is a browser-based multilingual IMAP client with an application-like user interface. It provides full functionality you expect from an email client, including MIME support, address book, folder manipulation, message searching and spell checking.

### YunoHost specific features

- Synchronize your email aliases as identities in Roundcube
- Install the [contextmenu](https://packagist.org/packages/johndoh/contextmenu) and [automatic addressbook](https://packagist.org/packages/projectmyst/automatic_addressbook) plugins by default
- Allow to install the [CardDAV](https://packagist.org/packages/roundcube/carddav) (address book) synchronization plugin at the installation - note that if you have installed Nextcloud or Baïkal, it will automatically add the corresponding and existing address book.
- Support for PGP encryption with Enigma plugin by default.


**Shipped version:** 1.6.7~ynh1

**Demo:** <https://demo.yunohost.org/webmail/>

## Screenshots

![Screenshot of Roundcube](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://roundcube.net/>
- Official admin documentation: <https://github.com/roundcube/roundcubemail/wiki>
- Upstream app code repository: <https://github.com/roundcube/roundcubemail>
- YunoHost Store: <https://apps.yunohost.org/app/roundcube>
- Report a bug: <https://github.com/YunoHost-Apps/roundcube_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/roundcube_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/roundcube_ynh/tree/testing --debug
or
sudo yunohost app upgrade roundcube -u https://github.com/YunoHost-Apps/roundcube_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
