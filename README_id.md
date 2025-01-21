<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# LocalAI untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/localai)](https://ci-apps.yunohost.org/ci/apps/localai/)
![Status kerja](https://apps.yunohost.org/badge/state/localai)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/localai)

[![Pasang LocalAI dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=localai)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang LocalAI secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

LocalAI is the free, Open Source OpenAI alternative. LocalAI act as a drop-in replacement REST API that’s compatible with OpenAI (Elevenlabs, Anthropic... ) API specifications for local AI inferencing. It allows you to run LLMs, generate images, audio (and not only) locally or on-prem with consumer grade hardware, supporting multiple model families. Does not require GPU.


**Versi terkirim:** 2.25.0~ynh1

## Tangkapan Layar

![Tangkapan Layar pada LocalAI](./doc/screenshots/331878853-20b5ccd2-8393-44f0-aaf6-87a23806381e.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://localai.io/>
- Depot kode aplikasi hulu: <https://github.com/mudler/LocalAI>
- Gudang YunoHost: <https://apps.yunohost.org/app/localai>
- Laporkan bug: <https://github.com/YunoHost-Apps/localai_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/localai_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
atau
sudo yunohost app upgrade localai -u https://github.com/YunoHost-Apps/localai_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
