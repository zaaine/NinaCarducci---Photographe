# Nina Carducci Photography - Optimisation SEO

Ce projet avait pour objectif d'améliorer la performance SEO (Search Engine Optimization) du site de Nina Carducci, photographe professionnelle. Des modifications ont été apportées pour améliorer la visibilité du site sur les moteurs de recherche, optimiser les performances, et garantir une meilleure expérience utilisateur.

## Objectifs du Projet

1. **Optimisation SEO** :
   - Ajout de balises `meta` appropriées (description, robots, Open Graph, etc.).
   - Utilisation des balises `alt` sur toutes les images pour améliorer l'accessibilité et le référencement.
   - Amélioration des balises HTML (ajout de `lang`, réorganisation des balises de titre).
2. **Optimisation des images** :

   - Conversion des images au format **WebP** pour réduire le temps de chargement et améliorer la performance du site.
   - Ajout d'attributs `srcset` et `sizes` pour un affichage réactif des images.
   - Implémentation de l'attribut `loading="lazy"` pour différer le chargement des images en dehors de l'écran visible.

3. **Améliorations du contenu HTML** :
   - Ajout de balises sémantiques (`header`, `main`, `section`, `nav`) pour améliorer la structure du site.
   - Utilisation de balises de titre (`h1`, `h2`, `h3`, etc.) de manière cohérente.
4. **Intégration des balises Open Graph** :
   - Ajout des balises Open Graph pour un meilleur partage sur les réseaux sociaux (Facebook, Instagram, etc.).
5. **Optimisation des performances** :
   - Minification des fichiers CSS et JavaScript.
   - Utilisation de `preconnect` pour améliorer les temps de connexion aux polices externes.

## Modifications Clés

### SEO

- Ajout des balises **`meta`** pour une meilleure indexation :
  - `<meta name="description">` : description du site pour les moteurs de recherche.
  - `<meta name="robots" content="index, follow">` : autorisation des robots à indexer et suivre les liens.
  - **Balises Open Graph** pour un partage optimisé sur les réseaux sociaux :
    - `<meta property="og:title">`, `<meta property="og:description">`, `<meta property="og:image">`.

### Optimisation des Images

- Conversion des images en format **WebP** :
  - Réduction de la taille des fichiers pour améliorer le temps de chargement.
  - Ajout de l'attribut **`srcset`** pour la prise en charge des résolutions d'écran différentes.

### Améliorations HTML

- Ajout de l'attribut **`lang="fr"`** dans la balise `<html>` pour améliorer l'accessibilité et l'indexation multilingue.
- Réorganisation des balises de titre pour une hiérarchie correcte (`h1`, `h2`, `h3`).
- Amélioration de la structure sémantique du document avec des balises comme `<header>`, `<main>`, `<section>`, `<nav>`.

### Optimisations des Scripts et CSS

- Minification des fichiers CSS et JavaScript pour réduire la taille des fichiers.
- Ajout de l'attribut **`async`** pour les fichiers JavaScript afin d'améliorer la performance de chargement.

## Installation et Démarrage

### Prérequis

Assurez-vous d'avoir installé les outils suivants sur votre machine :

- **Node.js** (version 14.x ou plus récente).
- **Yarn** ou **npm** pour la gestion des dépendances.

### Étapes d'installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/zaaine/ninacarducci.git
   ```

![Screenshot projet finalisé] (images/NinnaCarducci_screen.webp)

By Zaaine Aziz
