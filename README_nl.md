<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Adminer voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/adminer)](https://ci-apps.yunohost.org/ci/apps/adminer/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/adminer)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/adminer)

[![Adminer met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Adminer snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Geleverde versie:** 4.17.1~ynh1

**Demo:** <https://demo.adminer.org/adminer.php?username=>

## Schermafdrukken

![Schermafdrukken van Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Anti-eigenschappen

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentatie en bronnen

- Officiele website van de app: <https://docs.adminerevo.org/>
- Upstream app codedepot: <https://github.com/adminerevo/adminerevo>
- YunoHost-store: <https://apps.yunohost.org/app/adminer>
- Meld een bug: <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
of
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
