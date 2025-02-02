<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# LocalAI para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/localai)](https://ci-apps.yunohost.org/ci/apps/localai/)
![Estado funcional](https://apps.yunohost.org/badge/state/localai)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/localai)

[![Instalar LocalAI con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=localai)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarLocalAI rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

LocalAI is the free, Open Source OpenAI alternative. LocalAI act as a drop-in replacement REST API that’s compatible with OpenAI (Elevenlabs, Anthropic... ) API specifications for local AI inferencing. It allows you to run LLMs, generate images, audio (and not only) locally or on-prem with consumer grade hardware, supporting multiple model families. Does not require GPU.


**Versión actual:** 2.25.0~ynh2

## Capturas

![Captura de LocalAI](./doc/screenshots/331878853-20b5ccd2-8393-44f0-aaf6-87a23806381e.png)

## Documentaciones y recursos

- Sitio web oficial: <https://localai.io/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/mudler/LocalAI>
- Catálogo YunoHost: <https://apps.yunohost.org/app/localai>
- Reportar un error: <https://github.com/YunoHost-Apps/localai_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/localai_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
o
sudo yunohost app upgrade localai -u https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
