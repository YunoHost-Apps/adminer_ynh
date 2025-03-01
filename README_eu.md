<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Adminer YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/adminer)](https://ci-apps.yunohost.org/ci/apps/adminer/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/adminer)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/adminer)

[![Instalatu Adminer YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Adminer YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Paketatutako bertsioa:** 4.17.1~ynh1

**Demoa:** <https://demo.adminer.org/adminer.php?username=>

## Pantaila-argazkiak

![Adminer(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://docs.adminerevo.org/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/adminerevo/adminerevo>
- YunoHost Denda: <https://apps.yunohost.org/app/adminer>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
edo
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
