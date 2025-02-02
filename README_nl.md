<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# LocalAI voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/localai)](https://ci-apps.yunohost.org/ci/apps/localai/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/localai)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/localai)

[![LocalAI met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=localai)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je LocalAI snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

LocalAI is the free, Open Source OpenAI alternative. LocalAI act as a drop-in replacement REST API that’s compatible with OpenAI (Elevenlabs, Anthropic... ) API specifications for local AI inferencing. It allows you to run LLMs, generate images, audio (and not only) locally or on-prem with consumer grade hardware, supporting multiple model families. Does not require GPU.


**Geleverde versie:** 2.25.0~ynh2

## Schermafdrukken

![Schermafdrukken van LocalAI](./doc/screenshots/331878853-20b5ccd2-8393-44f0-aaf6-87a23806381e.png)

## Documentatie en bronnen

- Officiele website van de app: <https://localai.io/>
- Upstream app codedepot: <https://github.com/mudler/LocalAI>
- YunoHost-store: <https://apps.yunohost.org/app/localai>
- Meld een bug: <https://github.com/YunoHost-Apps/localai_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/localai_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
of
sudo yunohost app upgrade localai -u https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
