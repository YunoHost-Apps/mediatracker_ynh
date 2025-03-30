<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# MediaTracker pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/mediatracker)](https://ci-apps.yunohost.org/ci/apps/mediatracker/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/mediatracker)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/mediatracker)

[![Installer MediaTracker avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mediatracker)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer MediaTracker rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Plateforme auto-hébergée pour le suivi des films, des séries télévisées, des jeux vidéo, des livres et des livres audio, fortement inspirée par flox.

### Caractéristiques

- notifications
- calendrier
- utilisateurs multiples
- API REST
- liste de surveillance
- image docker
- import de Trakt
- import de goodreads


**Version incluse :** 0.2.11~ynh2

**Démo :** <https://mediatracker.app/>

## Captures d’écran

![Capture d’écran de MediaTracker](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/bonukai/MediaTracker>
- YunoHost Store : <https://apps.yunohost.org/app/mediatracker>
- Signaler un bug : <https://github.com/YunoHost-Apps/mediatracker_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/mediatracker_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mediatracker_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mediatracker -u https://github.com/YunoHost-Apps/mediatracker_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
