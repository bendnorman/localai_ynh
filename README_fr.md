<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# LocalAI pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/localai)](https://ci-apps.yunohost.org/ci/apps/localai/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/localai)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/localai)

[![Installer LocalAI avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=localai)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer LocalAI rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

LocalAI est l'alternative gratuite et Open Source à OpenAI. LocalAI agit comme une API REST de remplacement qui est compatible avec les spécifications de l'API OpenAI (Elevenlabs, Anthropic...) pour l'inférence IA locale. Elle vous permet d'exécuter des LLM, de générer des images, de l'audio (et pas seulement) localement ou sur site avec du matériel grand public, en prenant en charge plusieurs familles de modèles. Ne nécessite pas de GPU.

**Version incluse :** 2.25.0~ynh1

## Captures d’écran

![Capture d’écran de LocalAI](./doc/screenshots/331878853-20b5ccd2-8393-44f0-aaf6-87a23806381e.png)

## Documentations et ressources

- Site officiel de l’app : <https://localai.io/>
- Dépôt de code officiel de l’app : <https://github.com/mudler/LocalAI>
- YunoHost Store : <https://apps.yunohost.org/app/localai>
- Signaler un bug : <https://github.com/YunoHost-Apps/localai_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/localai_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
ou
sudo yunohost app upgrade localai -u https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
