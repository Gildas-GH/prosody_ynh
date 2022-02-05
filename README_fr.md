# Prosody pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/prosody.svg)](https://dash.yunohost.org/appci/app/prosody) ![](https://ci-apps.yunohost.org/ci/badges/prosody.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prosody.maintain.svg)  
[![Installer Prosody avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prosody)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Prosody rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Prosody is a modern XMPP communication server. It aims to be easy to set up and configure, and efficient with system resources. Additionally, for developers it aims to be easy to extend and give a flexible system on which to rapidly develop added functionality, or prototype new protocols.


**Version incluse :** 0.11.11~ynh1



## Avertissements / informations importantes

* Prosody will not replace the XMPP service Metronome integrated in YunoHost, it has been implemented for some specific apps that require Prosody

## Documentations et ressources

* Site officiel de l'app : https://prosody.im/
* Documentation officielle de l'admin : https://prosody.im/doc
* Dépôt de code officiel de l'app : https://hg.prosody.im/
* Documentation YunoHost pour cette app : https://yunohost.org/app_prosody
* Signaler un bug : https://github.com/YunoHost-Apps/prosody_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/prosody_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prosody_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prosody -u https://github.com/YunoHost-Apps/prosody_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps