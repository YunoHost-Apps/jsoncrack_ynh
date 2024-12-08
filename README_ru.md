<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# JSON Crack для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/jsoncrack)](https://ci-apps.yunohost.org/ci/apps/jsoncrack/)
![Состояние работы](https://apps.yunohost.org/badge/state/jsoncrack)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/jsoncrack)

[![Установите JSON Crack с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jsoncrack)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить JSON Crack быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

JSON Crack is a tool for visualizing JSON, YAML, CSV, XML, and TOML data in interactive graphs, making files easier to explore, format, and validate. It includes the following features:
- Visualizer: Instantly convert JSON, YAML, CSV, XML, and TOML into interactive graphs or trees in dark or light mode.
- Convert: Seamlessly transform data formats, like JSON to CSV or XML to JSON, for easy sharing.
- Format & Validate: Beautify and validate JSON, YAML, and CSV for clear and accurate data.
- Code Generation: Generate TypeScript interfaces, Golang structs, and JSON Schema.
- JSON Schema: Create JSON Schema, mock data, and validate various data formats.
- Advanced Tools: Decode JWT, randomize data, and run jq or JSON path queries.
- Export Image: Download your visualization as PNG, JPEG, or SVG.
- Privacy: All data processing is performed client-side; nothing is stored on the server.


**Поставляемая версия:** 2024.11.19~ynh2

**Демо-версия:** <https://jsoncrack.com/editor>

## Снимки экрана

![Снимок экрана JSON Crack](./doc/screenshots/jsoncrack.png)

## Документация и ресурсы

- Официальная документация пользователя: <https://jsoncrack.com/docs>
- Репозиторий кода главной ветки приложения: <https://github.com/AykutSarac/jsoncrack.com>
- Магазин YunoHost: <https://apps.yunohost.org/app/jsoncrack>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/jsoncrack_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
или
sudo yunohost app upgrade jsoncrack -u https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
