# PrettyNoemieCMS pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/prettynoemiecms.svg)](https://dash.yunohost.org/appci/app/prettynoemiecms)  
[![Install prettynoemiecms with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=prettynoemiecms)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer prettynoemiecms rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
CMS offrant à ses utilisateurs une solution ergonomique, simple et élégante pour construire en un rien de temps des sites vitrines responsives au design moderne.
La construction de votre site consistera à agencer à votre convenance des modules variés, d'éditer leurs contenus, et de personnaliser votre site en choisissant les polices de caractère, la mise en forme du texte, ainsi que les couleurs d'affichage.

**Version incluse:** 2019.05.23

## Captures d'écran

![](https://framablog.org/wp-content/uploads/2018/02/pages-framasite-theme-light.gif)

## Démo

* [Démo officielle](https://demo-pretty-noemie.frama.site)

Connectez-vous avec :

    login : pretty
    mdp : 12345678


## Configuration

Comment configurer cette application: via le panneau d'administration à : `votre.domain.tld/votre_chemin/admin`

## Documentation

 * Documentation officielle: https://framagit.org/framasoft/PrettyNoemieCMS

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge? **NON**  
L'application peut-elle être utilisée par plusieurs utilisateurs? **NON**

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/prettynoemiecms%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/prettynoemiecms/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/prettynoemiecms%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/prettynoemiecms/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/prettynoemiecms%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/prettynoemiecms/)

**Plus d'informations sur la page de documentation:**  
https://yunohost.org/packaging_apps

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/prettynoemiecms_ynh/issues
 * Site de l'application: https://framagit.org/framasoft/PrettyNoemieCMS
 * Dépôt de l'application principale: https://framagit.org/framasoft/PrettyNoemieCMS
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prettynoemiecms -u https://github.com/YunoHost-Apps/prettynoemiecms_ynh/tree/testing --debug
```
