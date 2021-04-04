# The Lounge pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/thelounge.svg)](https://dash.yunohost.org/appci/app/thelounge) ![](https://ci-apps.yunohost.org/ci/badges/thelounge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/thelounge.maintain.svg)  
[![Installer The Lounge avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=thelounge)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer The Lounge rapidement et simplement sur un serveur YunoHost.  
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble
The Lounge est un client Web IRC auto-hébergé.

**Version incluse :** 4.2.0

## Captures d’écran

![](https://raw.githubusercontent.com/thelounge/thelounge.github.io/master/img/thelounge-screenshot.png)

## Démo

* [Démo officielle](https://demo.thelounge.chat/)

## Configuration

Comment configurer cette application : via le panneau d’administration.

## Documentation

 * Documentation officielle : https://thelounge.chat/docs
 * Documentation YunoHost : https://yunohost.org/fr/app_thelounge

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

* L’authentification LDAP est-elle prise en charge ? **Oui**
* L’application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/thelounge.svg)](https://ci-apps.yunohost.org/ci/apps/thelounge/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/thelounge.svg)](https://ci-apps-arm.yunohost.org/ci/apps/thelounge/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/thelounge_ynh/issues
 * Site de l’application : https://thelounge.chat/
 * Dépôt de l’application principale : https://github.com/thelounge/thelounge
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
ou
sudo yunohost app upgrade thelounge -u https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
```
