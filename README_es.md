<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Adminer para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/adminer)](https://ci-apps.yunohost.org/ci/apps/adminer/)
![Estado funcional](https://apps.yunohost.org/badge/state/adminer)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/adminer)

[![Instalar Adminer con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarAdminer rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Versión actual:** 4.17.1~ynh1

**Demo:** <https://demo.adminer.org/adminer.php?username=>

## Capturas

![Captura de Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentaciones y recursos

- Sitio web oficial: <https://docs.adminerevo.org/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/adminerevo/adminerevo>
- Catálogo YunoHost: <https://apps.yunohost.org/app/adminer>
- Reportar un error: <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
o
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
