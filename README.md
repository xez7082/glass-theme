# 💎 Glassmorphism Blue Neon Theme for Home Assistant

Un thème moderne et immersif pour Home Assistant, basé sur l'esthétique **Glassmorphism** (effet de verre dépoli) et des accents **Néon Cyan (#00f9f9)**. Inspiré par le design "Lumina".

## ✨ Caractéristiques

* **Glassmorphism profond** : Effet de flou dynamique (`backdrop-filter`) sur toutes les cartes.
* **Accents Néon** : Bordures et icônes en bleu vibrant `#00f9f9`.
* **Interactivité (Hover)** : Les cartes s'élèvent et s'illuminent au passage de la souris.
* **Scrollbar Stylisée** : Barre de défilement ultra-fine et lumineuse.
* **Finition "Glossy"** : Reflets de lumière subtils intégrés aux cartes.

## 📸 Aperçu

> [!TIP]
> Le rendu est optimal avec un fond d'écran sombre et fluide. Le thème utilise l'image `f.png` présente dans ce dépôt.

## 🛠 Installation

### 1. Prérequis
Assurez-vous que [Card-Mod](https://github.com/thomasloven/lovelace-card-mod) est installé via HACS. C'est indispensable pour les effets de flou et de bordures.

### 2. Téléchargement
1. Copiez le fichier `glass_theme.yaml` dans votre dossier `themes/` de Home Assistant.
2. Ajoutez la ligne suivante à votre `configuration.yaml` si ce n'est pas déjà fait :
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
