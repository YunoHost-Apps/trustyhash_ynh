<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# TrustyHash YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/trustyhash.svg)](https://ci-apps.yunohost.org/ci/apps/trustyhash/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/trustyhash.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/trustyhash.maintain.svg)

[![Instalatu TrustyHash YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=trustyhash)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek TrustyHash YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

TrustyHash is a small [client-side](https://unhosted.org/) web application that
computes SHA-256 hash values on both local files and on remote URLs, with a
strong emphasis on a process that will allow you to trust the results.


**Paketatutako bertsioa:** 2016.06.17~ynh2

**Demoa:** <https://sprin.github.io/TrustyHash/>
## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/sprin/TrustyHash>
- YunoHost Denda: <https://apps.yunohost.org/app/trustyhash>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/trustyhash_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/trustyhash_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/trustyhash_ynh/tree/testing --debug
edo
sudo yunohost app upgrade trustyhash -u https://github.com/YunoHost-Apps/trustyhash_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
