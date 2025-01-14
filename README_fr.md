# Application vide avec accès SFTP au répertoire Web personnalisé pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/my_webapp.svg)](https://dash.yunohost.org/appci/app/my_webapp) ![](https://ci-apps.yunohost.org/ci/badges/my_webapp.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/my_webapp.maintain.svg)  
[![Installer Custom Webapp avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=my_webapp)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer une Application vide avec accès SFTP au répertoire Web personnalisé rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Cette application vous permet d'installer facilement une application vide personnalisée,
fourni un accès aux fichiers avec [SFTP](https://yunohost.org/fr/filezilla). Elle peut également créer une base de données MySQL -
qui sera sauvegardée et restaurée avec votre application. Les détails de connexion
seront stockés dans le fichier `db_accesss.txt` situé dans le répertoire racine.

La version de PHP-FPM peut aussi être choisie, parmi 7.3, 7.4, et 8.0.

**Version incluse :** 1.0

## Informations additionnelles

#### Port SFTP

Vous avez peut-être changé le port SSH comme décrit dans cette section : 
[Modifier le port SSH](https://yunohost.org/fr/security#modify-the-ssh-port) ;
alors vous devriez utiliser ce port pour mettre à jour votre site Web avec SFTP. 

## Liens

 * Documentation YunoHost pour cette app : https://yunohost.org/fr/app_my_webapp
 * Signaler un bug : https://github.com/YunoHost-Apps/my_webapp_ynh/issues
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request dans la [branche testing](https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing --debug
ou
sudo yunohost app upgrade my_webapp -u https://github.com/YunoHost-Apps/my_webapp_ynh/tree/testing --debug
```
