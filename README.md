<p align="center">
  <a href="https://github.com/Darkos999/fdroid-privileged-magisk/releases/latest">
    <img src="https://img.shields.io/github/v/release/Darkos999/fdroid-privileged-magisk?label=version&color=blue" alt="Version">
  </a>
  <img src="https://img.shields.io/badge/Magisk-Module-blue">
  <img src="https://img.shields.io/badge/Android-13--15-green">
  <img src="https://img.shields.io/badge/License-MIT-lightgrey">
  <img src="https://img.shields.io/badge/Language-FR%20%7C%20EN-yellow">
</p>


# 📦 F-Droid Privileged Extension – Module Magisk

Ce module installe l’extension privilégiée de F-Droid via Magisk.  
✅ Compatible Android 13 à 15  
🧪 Testé sur Noble ROM (Samsung S9+)

---

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

Ce projet est proposé sous licence libre (à définir — MIT, GPL, etc.)

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

This project is released under an open license (to be defined — MIT, GPL, etc.)

