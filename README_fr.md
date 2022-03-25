# PrettyNoemie CMS pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/prettynoemiecms.svg)](https://dash.yunohost.org/appci/app/prettynoemiecms) ![](https://ci-apps.yunohost.org/ci/badges/prettynoemiecms.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prettynoemiecms.maintain.svg)  
[![Installer PrettyNoemie CMS avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prettynoemiecms)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer PrettyNoemie CMS rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

CMS offrant à ses utilisateurs une solution ergonomique, simple et élégante pour construire en un rien de temps des sites vitrines responsives au design moderne.
La construction de votre site consistera à agencer à votre convenance des modules variés, d'éditer leurs contenus, et de personnaliser votre site en choisissant les polices de caractère, la mise en forme du texte, ainsi que les couleurs d'affichage.

**Version incluse :** 2020.01.07~ynh2

**Démo :** https://demo-pretty-noemie.frama.site

## Captures d'écran

![](./doc/screenshots/pages-framasite-theme-light.gif)

## Avertissements / informations importantes

## Configuration

Comment configurer cette application: via le panneau d'administration à : `votre.domain.tld/votre_chemin/admin`

## Documentations et ressources

* Documentation officielle utilisateur : https://framagit.org/framasoft/PrettyNoemieCMS
* Dépôt de code officiel de l'app : https://framagit.org/framasoft/PrettyNoemieCMS
* Documentation YunoHost pour cette app : https://yunohost.org/app_prettynoemiecms
* Signaler un bug : https://github.com/YunoHost-Apps/prettynoemiecms_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prettynoemiecms -u https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps