<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# MediaTracker untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/mediatracker)](https://ci-apps.yunohost.org/ci/apps/mediatracker/)
![Status kerja](https://apps.yunohost.org/badge/state/mediatracker)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/mediatracker)

[![Pasang MediaTracker dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mediatracker)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang MediaTracker secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Self hosted platform for tracking movies, tv shows, video games, books and audiobooks, highly inspired by flox

### Features

- notifications
- calendar
- multiple users
- REST API
- watchlist
- docker image
- import from Trakt
- import from goodreads


**Versi terkirim:** 0.2.11~ynh1

**Demo:** <https://mediatracker.app/>

## Tangkapan Layar

![Tangkapan Layar pada MediaTracker](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/bonukai/MediaTracker>
- Gudang YunoHost: <https://apps.yunohost.org/app/mediatracker>
- Laporkan bug: <https://github.com/YunoHost-Apps/mediatracker_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/mediatracker_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mediatracker_ynh/tree/testing --debug
atau
sudo yunohost app upgrade mediatracker -u https://github.com/YunoHost-Apps/mediatracker_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
