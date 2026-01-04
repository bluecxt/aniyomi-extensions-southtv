<div align="center">

![Build APK](https://github.com/VOTRE_USERNAME/aniyomi-extensions/actions/workflows/build_apk.yml/badge.svg)

</div>

# ![app icon](./.github/readme-images/app-icon.png)Aniyomi Extensions - Fork avec SouthTV

Ce dépôt est un fork de [yuzono/aniyomi-extensions](https://github.com/yuzono/aniyomi-extensions) avec l'ajout de l'extension **SouthTV** pour accéder au contenu de [southtv.fr](https://southtv.fr).

## Extension SouthTV

L'extension SouthTV permet de regarder du contenu vidéo depuis le site southtv.fr directement dans Aniyomi/Anikku.

**Langue :** Français (🇫🇷)

## À propos

Anikku/Aniyomi est un lecteur de manga et anime gratuit et open source pour Android 6.0 et plus.

Ce dépôt contient les extensions disponibles pour les forks [Anikku](https://github.com/komikku-app/anikku) ou [Aniyomi](https://github.com/aniyomiorg/aniyomi).

## Installation

### Téléchargement des APK

Les fichiers APK compilés seront disponibles dans la section [Releases](https://github.com/VOTRE_USERNAME/aniyomi-extensions/releases) de ce dépôt après chaque build.

Vous pouvez également compiler les extensions vous-même (voir la section Compilation ci-dessous).

## Compilation

Pour compiler l'extension SouthTV (ou toutes les extensions) :

```bash
# Compiler uniquement SouthTV
./gradlew assembleRelease -Pextensions=fr:southtv

# Compiler toutes les extensions
./gradlew assembleRelease
```

Les APK seront générés dans `src/[langue]/[extension]/build/outputs/apk/release/`

# Usage

Extension sources can be downloaded, installed, and uninstalled via the main Anikku app. They are installed and uninstalled like regular apps, in `.apk` format.

## Downloads

If you prefer to directly download the APK files, they are available via [website](https://yuzono.github.io/extensions-aniyomi/) or directly in this GitHub repository in the [`repo` branch](https://github.com/yuzono/anime-repo/tree/repo/apk).

# Requests

Source requests here are meant as up-for-grabs for any developer, thus it's impossible to provide a time estimation for any of them. Furthermore, some sites are impossible to do, usually because of various technical reasons.

## Contributing

Contributions are welcome!

Check out the repo's [issue backlog](https://github.com/yuzono/aniyomi-extensions/issues) for source requests and bug reports.

To get started with development, see [CONTRIBUTING.md](./CONTRIBUTING.md).

It might also be good to read our [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).

## Disclaimer

This project does not have any affiliation with the content providers available.
This project is not affiliated with Anikku or Aniyomi.
Don't ask for help about these extensions at the official support means of Anikku or Aniyomi.

All credits to the codebase goes to the original contributors.

## Crédits

- Projet original : [yuzono/aniyomi-extensions](https://github.com/yuzono/aniyomi-extensions)
- Extension SouthTV : Ajoutée dans ce fork
