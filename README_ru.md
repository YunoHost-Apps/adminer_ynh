<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Adminer для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/adminer)](https://ci-apps.yunohost.org/ci/apps/adminer/)
![Состояние работы](https://apps.yunohost.org/badge/state/adminer)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/adminer)

[![Установите Adminer с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Adminer быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Поставляемая версия:** 4.17.1~ynh1

**Демо-версия:** <https://demo.adminer.org/adminer.php?username=>

## Снимки экрана

![Снимок экрана Adminer](./doc/screenshots/screenshot.png)

## :red_circle: Анти-функции

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.adminer.org/>
- Репозиторий кода главной ветки приложения: <https://github.com/vrana/adminer/>
- Магазин YunoHost: <https://apps.yunohost.org/app/adminer>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/adminer_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
или
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
