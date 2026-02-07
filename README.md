# 💎 Glassmorphism Blue Neon Theme

[![HACS](https://img.shields.io/badge/HACS-Default-blue.svg)](https://github.com/hacs/integration)
![Version](https://img.shields.io/github/v/release/xez7082/glass-theme?include_prereleases)
[![License](https://img.shields.io/github/license/xez7082/glass-theme)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/xez7082/glass-theme/graphs/commit-activity)

Un thème moderne et immersif pour Home Assistant, basé sur l'esthétique **Glassmorphism** (effet de verre dépoli) et des accents **Néon Cyan (#00f9f9)**.

---

## ✨ Caractéristiques

* **Glassmorphism profond** : Effet de flou dynamique (`backdrop-filter`) sur toutes les cartes.
* **Accents Néon** : Bordures et icônes en bleu vibrant `#00f9f9`.
* **Interactivité (Hover)** : Les cartes s'élèvent et s'illuminent au passage de la souris.
* **Icônes Vivantes** : Effet de halo lumineux (Glow) sur les icônes actives.
* **Scrollbar Stylisée** : Barre de défilement ultra-fine et lumineuse.

## 📸 Installation

### 1. Prérequis
Vous devez impérativement avoir installé [Card-Mod](https://github.com/thomasloven/lovelace-card-mod) via HACS pour que les effets visuels fonctionnent.

### 2. Téléchargement
1. Copiez le fichier `glass_theme.yaml` dans votre dossier `themes/` de Home Assistant.
2. Ajoutez ceci à votre `configuration.yaml` :
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
