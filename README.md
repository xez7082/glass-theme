# 💎 Glass Theme for Home Assistant

Un thème moderne et épuré de type **Glassmorphism**, inspiré par le design de la carte *Lumina Energy*. Ce thème apporte un effet de verre dépoli (blur), des bordures lumineuses subtiles et une interface minimaliste à votre tableau de bord Home Assistant.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![HACS](https://img.shields.io/badge/HACS-Custom-orange.svg)

---

## ✨ Caractéristiques
* 🌫️ **Effet Verre Dépoli** : Utilisation du `backdrop-filter` pour un flou élégant.
* 🌑 **Optimisé pour le Mode Sombre** : Conçu pour reposer les yeux tout en restant lisible.
* 📱 **Design Responsif** : S'adapte parfaitement sur mobile et tablette.
* 🔗 **Style Lumina** : Intégration visuelle parfaite avec les cartes d'énergie modernes.

---

## 🛠 Prérequis

Pour obtenir l'effet de flou (blur), vous **devez** installer l'extension suivante via HACS :
* [**Card Mod**](https://github.com/thomasloven/lovelace-card-mod)

---

## 🚀 Installation

### Via HACS (Recommandé)
1. Ouvrez **HACS** dans votre instance Home Assistant.
2. Allez dans la section **Frontend**.
3. Cliquez sur les 3 points en haut à droite et sélectionnez **Dépôts personnalisés**.
4. Collez l'URL de ce dépôt : `https://github.com/TON_PSEUDO/glass-theme`
5. Sélectionnez la catégorie **Thème** et cliquez sur **Ajouter**.
6. Cliquez sur "Télécharger" sur la fiche du thème.

### Configuration YAML
Vérifiez que votre fichier `configuration.yaml` contient bien ceci :
```yaml
frontend:
  themes: !include_dir_merge_named themes
