# 🔄 Changelog

## v1.4 — Corrected release

---

### 🇫🇷 Version française

- ✅ Correction de la structure de l’archive `.zip` :
  - Suppression du dossier `files/`
  - Utilisation correcte de la hiérarchie `system/priv-app/F-DroidPrivileged/`

- 📦 Fichier APK renommé avec le nom exact du package Android :
  - `org.fdroid.fdroid.privileged.apk`

- 🛠️ Réécriture complète du script `install.sh` :
  - Suppression des variables non définies
  - Encodage corrigé : UTF-8 sans BOM, fin de ligne Unix (LF)
  - Script minimal conforme au format Magisk

- 🧪 Tests effectués sur appareil `system-as-root` :
  - Installation validée via Magisk Manager
  - Module fonctionnel après redémarrage

- 🌐 Mise à jour de la release GitHub avec le fichier `.zip` corrigé :
  - `fdroid-privileged-magisk-v1.3.zip`
  - Lien compatible avec `update.json`

---

### 🇬🇧 English version

- ✅ Fixed the `.zip` archive structure:
  - Removed the unnecessary `files/` directory
  - Correct hierarchy: `system/priv-app/F-DroidPrivileged/`

- 📦 Renamed the APK file to match exact Android package:
  - `org.fdroid.fdroid.privileged.apk`

- 🛠️ Rewrote the `install.sh` script:
  - Removed undefined variables
  - Corrected encoding: UTF-8 without BOM, Unix line endings (LF)
  - Minimal script following Magisk module format

- 🧪 Successfully tested on a system-as-root device:
  - Installation via Magisk Manager worked flawlessly
  - Module functional after reboot

- 🌐 GitHub release updated with fixed `.zip` file:
  - `fdroid-privileged-magisk-v1.3.zip`
  - Download link remains compatible with `update.json`