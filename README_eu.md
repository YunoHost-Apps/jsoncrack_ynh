<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# JSON Crack YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/jsoncrack)](https://ci-apps.yunohost.org/ci/apps/jsoncrack/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/jsoncrack)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/jsoncrack)

[![Instalatu JSON Crack YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jsoncrack)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek JSON Crack YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

JSON Crack is a tool for visualizing JSON, YAML, CSV, XML, and TOML data in interactive graphs, making files easier to explore, format, and validate. It includes the following features:
- Visualizer: Instantly convert JSON, YAML, CSV, XML, and TOML into interactive graphs or trees in dark or light mode.
- Convert: Seamlessly transform data formats, like JSON to CSV or XML to JSON, for easy sharing.
- Format & Validate: Beautify and validate JSON, YAML, and CSV for clear and accurate data.
- Code Generation: Generate TypeScript interfaces, Golang structs, and JSON Schema.
- JSON Schema: Create JSON Schema, mock data, and validate various data formats.
- Advanced Tools: Decode JWT, randomize data, and run jq or JSON path queries.
- Export Image: Download your visualization as PNG, JPEG, or SVG.
- Privacy: All data processing is performed client-side; nothing is stored on the server.


**Paketatutako bertsioa:** 2024.12.12~ynh5

**Demoa:** <https://jsoncrack.com/editor>

## Pantaila-argazkiak

![JSON Crack(r)en pantaila-argazkia](./doc/screenshots/jsoncrack.png)

## Dokumentazioa eta baliabideak

- Erabiltzaileen dokumentazio ofiziala: <https://jsoncrack.com/docs>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/AykutSarac/jsoncrack.com>
- YunoHost Denda: <https://apps.yunohost.org/app/jsoncrack>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/jsoncrack_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
edo
sudo yunohost app upgrade jsoncrack -u https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
