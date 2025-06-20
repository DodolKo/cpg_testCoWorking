# Présentation du projet

Ce projet est un petit site web pour présenter une bière artisanale.

## Structure du projet

- `src/` : Contient le code source du site
  - `index.html` : Page principale
  - `js/` : Scripts JavaScript
  - `style/` : Fichiers SCSS pour le style
    - `global.scss` : Fichier principal SCSS
    - `Layout/` : SCSS pour l'en-tête et le pied de page
- `dist/` : Dossier de sortie pour les fichiers compilés (notamment `style.css`)

## Installation et utilisation

1. **Installer les dépendances**

```bash
npm install
```

2. **Compiler le SCSS**

Pour compiler le SCSS en CSS dans le dossier `dist` :

```bash
npm run build:scss
```

3. **Lancer le site**

Ouvrez `dist/index.html` dans votre navigateur.

## Objectif

Créer une page web moderne et attractive pour mettre en avant une bière, avec une présentation, des images et un design responsive.
