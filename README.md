 # 📦 F-Droid Privileged Extension – Module Magisk

> Installe automatiquement l’extension privilégiée de F-Droid sur Android 13 à 15 via Magisk.  
> Testé sur Noble ROM (Samsung S9+)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  
![Version](https://img.shields.io/badge/version-v1.3-orange)  
![Android](https://img.shields.io/badge/Android-13--15-green)

---

## 🧭 Sommaire

- [📥 Installation](#installation)
- [⚙️ Fonctionnalités](#fonctionnalités)
- [📲 Utilisation](#utilisation)
- [📦 Structure du module](#structure-du-module)
- [📝 Changelog](#changelog)
- [🙏 Remerciements](#remerciements)
- [📜 Licence](#licence)

---

## 📥 Installation

1. Télécharge le fichier `.zip` depuis la release **v1.3**
2. Ouvre Magisk > Modules
3. Sélectionne le fichier : `fdroid-privileged-magisk-v1.3.zip`
4. Redémarre ton appareil une fois l’installation terminée ✅

➡️ Ou installe automatiquement via l’URL `update.json` :



<p align="center">
  <a href="https://github.com/Darkos999/fdroid-privileged-magisk/releases/latest">
    <img src="https://img.shields.io/github/v/release/Darkos999/fdroid-privileged-magisk?label=version&color=blue" alt="Version">
  </a>
  <img src="https://img.shields.io/badge/Magisk-Module-blue">
  <img src="https://img.shields.io/badge/Android-13--15-green">
 
  [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
  
  <img src="https://img.shields.io/badge/Language-FR%20%7C%20EN-yellow">
</p>


# 📦 F-Droid Privileged Extension – Module Magisk

Ce module installe l’extension privilégiée de F-Droid via Magisk.  
✅ Compatible Android 13 à 15  
🧪 Testé sur Noble ROM (Samsung S9+)

---
## 🧭 Sommaire
- [📥 Installation](#installation)
- [⚙️ Fonctionnalités](#fonctionnalités)
- [📲 Utilisation](#utilisation)
- [📦 Structure du module](#structure-du-module)
- [📝 Changelog](#changelog)
- [🙏 Remerciements](#remerciements)
- [📜 Licence](#licence)

📦 **Installation**
- Télécharge le fichier `.zip` depuis la [release v1.3](https://github.com/Darkos999/fdroid-privileged-magisk/releases/latest)
- Installe-le via Magisk Manager

🔗 **update.json**  
Utilise ce lien dans Magisk :  
`https://raw.githubusercontent.com/Darkos999/fdroid-privileged-magisk/main/update.json`

👤 **Auteur**  
Eric Lange & Copilot

---

## 🧰 Fonctionnalités

- 📲 Intégration système de l’APK `org.fdroid.fdroid.privileged`
- 🔒 Fonctionne avec les appareils system-as-root
- 🚀 Installation automatique via Magisk, sans action manuelle
- 🔄 Compatible avec les mises à jour Magisk

---

## 📁 Structure de l'archive `.zip`

```
fdroid-privileged-magisk-v1.3.zip  
├── module.prop  
├── install.sh  
└── system/  
    └── priv-app/  
        └── F-DroidPrivileged/  
            └── org.fdroid.fdroid.privileged.apk
```

> 📦 L’APK doit être exactement nommé : `org.fdroid.fdroid.privileged.apk`

---

## 📥 Installation

1. Ouvrir Magisk > Modules  
2. Choisir “Installer depuis le stockage”  
3. Sélectionner le fichier :  
   `fdroid-privileged-magisk-v1.3.zip`  
4. Redémarrer l’appareil une fois l’installation terminée ✅

---

## 🧭 Utilisation dans Magisk

- Ouvrez **F-Droid**  
- L’extension sera détectée automatiquement  
- Vous pourrez installer ou mettre à jour des applications **sans confirmation**

---

## 📝 Informations sur le module

```
id=fdroid-privileged-magisk
name=F-Droid Privileged Extension
version=v1.3
versionCode=3
author=Eric Lange & Copilot
description=Installe F-Droid Privileged Extension via Magisk pour intégration système.
```

---

## 📰 Changelog

Consultez [`CHANGELOG.md`](./CHANGELOG.md) pour les mises à jour et correctifs.

---

## 🤝 Remerciements

Merci à l’équipe F-Droid, à la communauté Magisk et aux utilisateurs qui testent et améliorent ce module !

---

## 📜 Licence

Ce projet est publié sous la licence libre **GNU GPL v3**.  
Consultez le fichier [`LICENSE`](./LICENSE) pour plus de détails.

---

# 📦 F-Droid Privileged Extension – Magisk Module

This module installs the F-Droid Privileged Extension via Magisk.  
✅ Compatible with Android 13 to 15  
🧪 Successfully tested on Noble ROM (Samsung S9+)

---

📦 **Installation**
- Download the `.zip` from the [v1.3 release](https://github.com/Darkos999/fdroid-privileged-magisk/releases/latest)
- Install it using Magisk Manager

🔗 **update.json**  
Use this link in Magisk:  
`https://raw.githubusercontent.com/Darkos999/fdroid-privileged-magisk/main/update.json`

👤 **Author**  
Eric Lange & Copilot

---

## 🧰 Features

- 📲 System-level integration of `org.fdroid.fdroid.privileged`
- 🔒 Supports system-as-root devices
- 🚀 Installs automatically via Magisk
- 🔄 Compatible with future Magisk updates

---

## 📁 Zip Archive Structure

```
fdroid-privileged-magisk-v1.3.zip  
├── module.prop  
├── install.sh  
└── system/  
    └── priv-app/  
        └── F-DroidPrivileged/  
            └── org.fdroid.fdroid.privileged.apk
```

> 📦 The APK must be named: `org.fdroid.fdroid.privileged.apk`

---

## 📥 Installation

1. Open Magisk > Modules  
2. Tap “Install from storage”  
3. Select: `fdroid-privileged-magisk-v1.3.zip`  
4. Reboot after installation ✅

---

## 🧭 Usage with Magisk

- Open **F-Droid**  
- The extension will be auto-detected  
- You can install/update apps silently

---

## 📝 Module Info

```
id=fdroid-privileged-magisk
name=F-Droid Privileged Extension
version=v1.3
versionCode=3
author=Eric Lange & Copilot
description=Installs F-Droid Privileged Extension via Magisk for system integration.
```

---

## 📰 Changelog

See [`CHANGELOG.md`](./CHANGELOG.md) for updates and bugfixes.

---

## 🤝 Thanks

Thanks to the F-Droid team, Magisk community, and users who test and improve this module!

---


## 📜 License

This project is released under the open source **GNU GPL v3** license.  
See the [`LICENSE`](./LICENSE) file for full details.

  ## 📜 Licence

Ce projet est publié sous la licence libre **GNU GPL v3**.  


Consultez le fichier [`LICENSE`](./LICENSE) pour plus de détails.

## 🤝 Contribuer

Les contributions sont les bienvenues !  
Tu peux proposer des améliorations, signaler des bugs ou soumettre des pull requests.

1. Fork le dépôt
2. Crée une branche (`git checkout -b amélioration-nouvelle`)
3. Commit tes changements (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. Push la branche (`git push origin amélioration-nouvelle`)
5. Ouvre une Pull Request

## ❓ Support

Si tu rencontres un problème avec ce module :

- Vérifie que tu utilises une version compatible de Magisk (≥ 24)
- Assure-toi que l’APK est bien nommé `org.fdroid.fdroid.privileged.apk`
- Consulte le fichier [`CHANGELOG.md`](./CHANGELOG.md) pour voir les dernières modifications

📬 Tu peux aussi ouvrir une [issue sur GitHub](https://github.com/Darkos999/fdroid-privileged-magisk/issues) pour signaler un bug ou poser une question.

Merci pour ton soutien 🙌


