<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# JSON Crack pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/jsoncrack)](https://ci-apps.yunohost.org/ci/apps/jsoncrack/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/jsoncrack)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/jsoncrack)

[![Installer JSON Crack avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=jsoncrack)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer JSON Crack rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

JSON Crack est un outil pour visualiser des données JSON, YAML, CSV, XML et TOML sous forme de graphes interactifs, rendant ces fichiers plus facile à explorer, à formater et à en vérifier la validité. Il inclut les fonctionnalités suivantes: 
- Visualisateur: Transforme instantanément des données JSON, YAML, CSV, XML et TOML en graphs interactifs ou en arbres de données avec un thème sombre et un thème clair.
- Convertisseur: Passe d'un des formats de données supportés à un autre afin de le partager sous la forme voulue.
- Validateur: Met en forme et vérifie la validité des données JSON, YAML et CSV pour obtenir des données claires et précises.
- Générateur de code: Génère automatiquement le code des interfaces TypeScript, des structs Golang, et des schémas JSON.
- Schémas JSON: Crée des schémas JSON, des modèles de données, et vérifier la validité de différents formats de données.
- Outils avancés: Decodage JWT, génération de données aléatoire, et exécution de requêtes jq ou JSON path.
- Export d'image: Offre de télécharger les visualisations sous forme d'images PNG, JPEG ou SVG.
- Confidentialité: Traitement des données côté client, rien n'est enregistré sur le serveur.


**Version incluse :** 2024.12.12~ynh6

**Démo :** <https://jsoncrack.com/editor>

## Captures d’écran

![Capture d’écran de JSON Crack](./doc/screenshots/jsoncrack.png)

## Documentations et ressources

- Documentation officielle utilisateur : <https://jsoncrack.com/docs>
- Dépôt de code officiel de l’app : <https://github.com/AykutSarac/jsoncrack.com>
- YunoHost Store : <https://apps.yunohost.org/app/jsoncrack>
- Signaler un bug : <https://github.com/YunoHost-Apps/jsoncrack_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
ou
sudo yunohost app upgrade jsoncrack -u https://github.com/YunoHost-Apps/jsoncrack_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
