<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# JSON Crack voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/jsoncrack)](https://ci-apps.yunohost.org/ci/apps/jsoncrack/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/jsoncrack)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/jsoncrack)

[![JSON Crack met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jsoncrack)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je JSON Crack snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

JSON Crack is a tool for visualizing JSON, YAML, CSV, XML, and TOML data in interactive graphs, making files easier to explore, format, and validate. It includes the following features:
- Visualizer: Instantly convert JSON, YAML, CSV, XML, and TOML into interactive graphs or trees in dark or light mode.
- Convert: Seamlessly transform data formats, like JSON to CSV or XML to JSON, for easy sharing.
- Format & Validate: Beautify and validate JSON, YAML, and CSV for clear and accurate data.
- Code Generation: Generate TypeScript interfaces, Golang structs, and JSON Schema.
- JSON Schema: Create JSON Schema, mock data, and validate various data formats.
- Advanced Tools: Decode JWT, randomize data, and run jq or JSON path queries.
- Export Image: Download your visualization as PNG, JPEG, or SVG.
- Privacy: All data processing is performed client-side; nothing is stored on the server.


**Geleverde versie:** 3.2.0~ynh1

**Demo:** <https://jsoncrack.com/editor>

## Schermafdrukken

![Schermafdrukken van JSON Crack](./doc/screenshots/jsoncrack.png)

## Documentatie en bronnen

- Officiele gebruikersdocumentatie: <https://jsoncrack.com/docs>
- Upstream app codedepot: <https://github.com/AykutSarac/jsoncrack.com>
- YunoHost-store: <https://apps.yunohost.org/app/jsoncrack>
- Meld een bug: <https://github.com/YunoHost-Apps/jsoncrack_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
of
sudo yunohost app upgrade jsoncrack -u https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
