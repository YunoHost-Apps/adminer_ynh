<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Adminer pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/adminer.svg)](https://dash.yunohost.org/appci/app/adminer) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)

[![Installer Adminer avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Adminer rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Adminer (anciennement phpMinAdmin) est un outil de gestion de base de données complet écrit en PHP. À l'inverse de phpMyAdmin, il se compose d'un seul fichier prêt à être déployé sur le serveur cible. Adminer est disponible pour MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB et autres via un plugin. 

**Version incluse :** 4.8.1~ynh7

**Démo :** <https://demo.adminer.org/adminer.php?username=>

## Captures d’écran

![Capture d’écran de Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://www.adminer.org/>
- Dépôt de code officiel de l’app : <https://github.com/vrana/adminer/>
- YunoHost Store : <https://apps.yunohost.org/app/adminer>
- Signaler un bug : <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
ou
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
