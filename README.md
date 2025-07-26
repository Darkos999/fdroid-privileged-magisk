> ⚠️ Ce module est en phase de test. Consultez la section "Statut & limitations" en bas de page pour plus d’infos.

# 🔧 fdroid-privileged-magisk

> Module Magisk pour activer l’extension privilégiée de F-Droid sans modification système 🔐

![GitHub release (latest by date)](https://img.shields.io/github/v/release/Darkos999/fdroid-privileged-magisk)
![GitHub repo size](https://img.shields.io/github/repo-size/Darkos999/fdroid-privileged-magisk)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)

---

## 📦 Fonctionnalités

- Installation **systemless** via Magisk
- Donne à F-Droid les **permissions système** pour installer, mettre à jour et supprimer des apps sans confirmation
- Compatible Android **8.0 et plus**
- Facilement désinstallable sans toucher à `/system`

---

## ⚙️ Prérequis

- Magisk ≥ v24
- F-Droid installé (version officielle ou custom)
- Accès root via Magisk

---

## 🚀 Installation

1. Télécharger le fichier ZIP depuis les [Releases GitHub](https://github.com/Darkos999/fdroid-privileged-magisk/releases)
2. Ouvrir Magisk > Modules > Installer depuis le stockage
3. Sélectionner le ZIP et redémarrer
4. Vérifier que l’extension est active dans F-Droid (`Paramètres > Extension privilégiée`)

---

## 🐞 Problèmes connus

- Certaines ROM verrouillées (OneUI, MIUI) peuvent bloquer l’installation
- Après une mise à jour Magisk, il peut être nécessaire de réactiver F-Droid

---

## 🧪 Développement

- Basé sur le travail de [laggardkernel](https://github.com/laggardkernel/fdroid-privileged-magisk) et [qianbinbin](https://github.com/qianbinbin/fdroid-priv-ext)
- Dépôt maintenu par [Darkos999](https://github.com/Darkos999) et collaborateurs

---

## 🤝 Contribuer

Les contributions sont les bienvenues ! Tu peux :
- Proposer des améliorations
- Signaler des bugs
- Créer des issues ou pull requests

---

## 📜 Licence

Ce projet est distribué sous licence **GNU GPLv3**.  
Consulte les termes sur [gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)

---

## 🧾 Notes complémentaires & historique

Ce module a été développé avec l’objectif de faciliter l’intégration de F-Droid dans les systèmes Android rootés, en évitant les manipulations manuelles via recovery.

Nous avons utilisé **VS Code** comme éditeur principal pour :
- Éditer et formater le `README.md`
- Gérer le dépôt GitHub
- Créer et structurer le module Magisk avec confort
- Collaborer plus efficacement en local avant mise en ligne

L’extension **Markdown PDF** a servi à exporter les docs `.md` en PDF pour la documentation offline.  
Ce projet est une contribution commune avec mise en dépôt publique sur GitHub.

---

## Statut & limitations

⚠️ Ce module est encore en phase de test.  
Certaines fonctions peuvent ne pas être pleinement opérationnelles selon l’environnement (version Android, Magisk…).  
Les retours sont les bienvenus pour améliorer sa compatibilité et sa stabilité 🛠️

##Release supprimée pour les raisons indiquées ci-dessous:

module toujours en test ( probleme avec magisk ).
