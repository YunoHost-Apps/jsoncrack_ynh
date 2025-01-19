<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 JSON Crack

[![集成程度](https://apps.yunohost.org/badge/integration/jsoncrack)](https://ci-apps.yunohost.org/ci/apps/jsoncrack/)
![工作状态](https://apps.yunohost.org/badge/state/jsoncrack)
![维护状态](https://apps.yunohost.org/badge/maintained/jsoncrack)

[![使用 YunoHost 安装 JSON Crack](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jsoncrack)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 JSON Crack。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

JSON Crack is a tool for visualizing JSON, YAML, CSV, XML, and TOML data in interactive graphs, making files easier to explore, format, and validate. It includes the following features:
- Visualizer: Instantly convert JSON, YAML, CSV, XML, and TOML into interactive graphs or trees in dark or light mode.
- Convert: Seamlessly transform data formats, like JSON to CSV or XML to JSON, for easy sharing.
- Format & Validate: Beautify and validate JSON, YAML, and CSV for clear and accurate data.
- Code Generation: Generate TypeScript interfaces, Golang structs, and JSON Schema.
- JSON Schema: Create JSON Schema, mock data, and validate various data formats.
- Advanced Tools: Decode JWT, randomize data, and run jq or JSON path queries.
- Export Image: Download your visualization as PNG, JPEG, or SVG.
- Privacy: All data processing is performed client-side; nothing is stored on the server.


**分发版本：** 2024.12.12~ynh4

**演示：** <https://jsoncrack.com/editor>

## 截图

![JSON Crack 的截图](./doc/screenshots/jsoncrack.png)

## 文档与资源

- 官方用户文档： <https://jsoncrack.com/docs>
- 上游应用代码库： <https://github.com/AykutSarac/jsoncrack.com>
- YunoHost 商店： <https://apps.yunohost.org/app/jsoncrack>
- 报告 bug： <https://github.com/YunoHost-Apps/jsoncrack_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
或
sudo yunohost app upgrade jsoncrack -u https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
