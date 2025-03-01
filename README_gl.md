<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Adminer para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/adminer)](https://ci-apps.yunohost.org/ci/apps/adminer/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/adminer)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/adminer)

[![Instalar Adminer con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Adminer de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Versión proporcionada:** 4.17.1~ynh1

**Demo:** <https://demo.adminer.org/adminer.php?username=>

## Capturas de pantalla

![Captura de pantalla de Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Debes considerar

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentación e recursos

- Web oficial da app: <https://docs.adminerevo.org/>
- Documentación oficial para admin: <https://docs.adminerevo.org/>
- Repositorio de orixe do código: <https://github.com/vrana/adminer>
- Tenda YunoHost: <https://apps.yunohost.org/app/adminer>
- Informar dun problema: <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
ou
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
