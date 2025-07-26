# imh-new-plugin, v0.0.1

cPanel and CWP plugin template.

- cPanel/WHM path: `/usr/local/cpanel/whostmgr/docroot/cgi/imh-new-plugin/index.php`
- CWP path: `/usr/local/cwpsrv/htdocs/resources/admin/modules/imh-new-plugin.php`

## Screenshot

![Screenshot](whm-plugin.png)

# Installation

- Run as the Root user: `curl -fsSL https://raw.githubusercontent.com/gemini2463/imh-new-plugin/master/install.sh | sh`

# Files

## Shell installer

- install.sh

## Main script

- index.php - Identical to `imh-new-plugin.php`.
- index.php.sha256 - `sha256sum index.php > index.php.sha256`
- imh-new-plugin.php - Identical to `index.php`.
- imh-new-plugin.php.sha256 - `sha256sum imh-new-plugin.php > imh-new-plugin.php.sha256`

## Javascript

- imh-new-plugin.js - Bundle React or any other javascript in this file.
- imh-new-plugin.js.sha256 - `sha256sum imh-new-plugin.js > imh-new-plugin.js.sha256`

## Icon

- imh-new-plugin.png - [48x48 png image](https://api.docs.cpanel.net/guides/guide-to-whm-plugins/guide-to-whm-plugins-plugin-files/#icons)
- imh-new-plugin.png.sha256 - `sha256sum imh-new-plugin.png > imh-new-plugin.png.sha256`

## cPanel conf
- imh-new-plugin.conf - [AppConfig Configuration File](https://api.docs.cpanel.net/guides/guide-to-whm-plugins/guide-to-whm-plugins-appconfig-configuration-file)
- imh-new-plugin.conf.sha256 - `sha256sum imh-new-plugin.conf > imh-new-plugin.conf.sha256`

## CWP include

- cwp-include.php - [CWP include](https://wiki.centos-webpanel.com/how-to-build-a-cwp-module)
- cwp-include.php.sha256 - `sha256sum cwp-include.php > cwp-include.php.sha256`

