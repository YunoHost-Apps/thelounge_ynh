# The Lounge pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/thelounge.svg)](https://dash.yunohost.org/appci/app/thelounge) ![](https://ci-apps.yunohost.org/ci/badges/thelounge.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/thelounge.maintain.svg)  
[![Installer The Lounge avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=thelounge)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer The Lounge rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Client Web IRC

**Version incluse :** 4.2.0~ynh3

**Démo :** https://demo.thelounge.chat/

## Captures d'écran

![](./doc/screenshots/thelounge-screenshot.png)

## Avertissements / informations importantes

## Configuration

Comment configurer cette application : via le panneau d’administration.

#### Support multi-utilisateurs

* L’authentification LDAP est-elle prise en charge ? **Oui**
* L’application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

## Documentations et ressources

* Site officiel de l'app : https://thelounge.chat/
* Documentation officielle de l'admin : https://thelounge.chat/docs
* Dépôt de code officiel de l'app : https://github.com/thelounge/thelounge
* Documentation YunoHost pour cette app : https://yunohost.org/app_thelounge
* Signaler un bug : https://github.com/YunoHost-Apps/thelounge_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
ou
sudo yunohost app upgrade thelounge -u https://github.com/YunoHost-Apps/thelounge_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps