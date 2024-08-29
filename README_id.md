<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Adminer untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/adminer.svg)](https://ci-apps.yunohost.org/ci/apps/adminer/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)

[![Pasang Adminer dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Adminer secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Versi terkirim:** 4.8.4~ynh1

**Demo:** <https://demo.adminer.org/adminer.php?username=>

## Tangkapan Layar

![Tangkapan Layar pada Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.adminer.org/>
- Depot kode aplikasi hulu: <https://github.com/vrana/adminer/>
- Gudang YunoHost: <https://apps.yunohost.org/app/adminer>
- Laporkan bug: <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
atau
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
