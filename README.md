# Transformez une maquette en site web

[![forthebadge](https://forthebadge.com/images/badges/validated-html5.svg)](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Farthurblanc.github.io%2FArthurBlanc_2_08102020%2F)
[![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://github.com/ArthurBlanc)

Lien du projet : https://arthurblanc.github.io/ArthurBlanc_2_08102020/

## Description :

Transformez une maquette en site web :

> Démarrez sur HTML et CSS en intégrant une page Web, d'une plateforme de réservation de vacances.
>
> #### Compétences évaluées
>
> -   Intégrer du contenu conformément à une maquette
> -   Mettre en place son environnement Front-End
> -   Utiliser un système de gestion de versions pour le suivi du projet et son hébergement
> -   Implémenter une interface responsive

### Situation (fictive) du projet :

Stagiaire développeur web dans une entreprise proposant un outil de planification de vacances.

L’UI Designer a proposé un nouveau design du site basé sur Material Design.

Mon rôle a été de réaliser le prototype du site en intégrant les maquettes en HTML et CSS.

[Voir les maquettes](#maquettes)

### Cahier des charges :

#### Contraintes techniques :

-   Respecter les maquettes Mobile et Desktop
-   Adapter le site pour les tablettes
-   Sélectionner le format d’image le plus adapté à la résolution et au temps de chargement
-   Utiliser la bibliothèque [Font Awesome](https://fontawesome.com/) en HTML ou CSS pour les icônes
-   Couleur de la charte graphique :
    -   Bleu : ![#0065FC](https://via.placeholder.com/15/0065FC/000000?text=+) `#0065FC`
    -   Bleu clair : ![#DEEBFF](https://via.placeholder.com/15/DEEBFF/000000?text=+) `#DEEBFF`
    -   Gris : ![#F2F2F2](https://via.placeholder.com/15/F2F2F2/000000?text=+) `#F2F2F2`
-   Police : [Raleway](https://fonts.google.com/specimen/Raleway)
-   **Pas de framework** : HTML et CSS _from scratch_
-   [Le code devra utiliser les balises sémantiques et ne doit contenir aucune erreur ni alerte au validateur W3C HTML et CSS.](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Farthurblanc.github.io%2FArthurBlanc_2_08102020%2F)
-   Le site doit être compatible avec les dernières versions de Chrome et Firefox
-   Séparer le HTML et le CSS et organiser le dossier de rendu
-   Versionner le code avec Git et déployer la page sur GitHub Pages ou GitLab Page
-   Recommendation :
    -   Utiliser _Visual Studio Code_
    -   Utiliser _Flexbox_

#### Fonctionnalités :

-   Un champ de recherche des villes (non fonctionnel)
-   Des cartes d’hébergements et d’activités cliquables dans leur intégralité
-   Les filtres thématiques (non fonctionnels) changent d’apparence au survol
-   Dans le menu, _Hébergements_ et _Activités_ sont des ancres menant à leur section respective de la page

## Notes sur la réalisation du projet et les choix techniques

-   **Temps de travail estimé :** environ 20-25h
-   **_Mobile First_**
-   **HTML 5**
    -   Balises sémantiques utilisées : `<header> <nav> <main> <section> <article> <aside> <footer>`
    -   Les icônes [Font Awesome](https://fontawesome.com/) sont intégrées dans le HTML (utilisation du CDN officiel pour intégrer le CSS de Font Awesome)
-   **CSS 3**
    -   _Flexbox_
    -   Import de la police [Raleway via CDN Google Font](https://fonts.google.com/specimen/Raleway)
-   **Images :** Sélection des images du dossier _small_ car leur résolution est suffisante pour l’affichage sur le site. De plus le format des images est le jpg, c’est le format le plus adapté pour l’affichage des photos sur un site internet.
    Les images sont contenues dans le dossier _assets/img_
-   **Dossier de rendu :** Le HTML de la page est contenu dans un fichier _index.html_ et le CSS est contenu dans un fichier _style.css_ dans le dossier _assets/css_

## Installation

-   **Executez Git bash**
-   **git clone https://github.com/ArthurBlanc/ArthurBlanc_2_08102020**

## Développé avec

-   [Visual Studio Code](https://code.visualstudio.com/) - Éditeur de texte et son intégration de GitHub
-   [Font Awesome](https://fontawesome.com/) - Bibliothèque d'icône
-   [Google Font : _Raleway_](https://fonts.google.com/specimen/Raleway) - Police _Raleway_ sur Google Font
-   [GitHub](https://github.com/) - Outil de gestion de versions
-   [GitHub Pages](https://pages.github.com/) - Outil d’hébergement

## Tags

-   **v1.3c** : Passage des valeurs VW en REM pour les layouts et refactoring du CSS
-   **v1.3b** : Ajout du README
-   **v1.3** : Refonte du HTML et CSS
-   **v1.2** : Ajout du CSS pour la version Tablet + ajout du code couleur
-   **v1.1** : Ajout du CSS pour la version Desktop
-   **v1.0b** : Modification de la taille de la police sur la classe .search-button
-   **v1.0** : Lancement du projet - Premier jet du HTML et CSS en mobile first

## Auteur

**Arthur Blanc** : [**GitHub**](https://github.com/ArthurBlanc/) - [**Portfolio**](https://abcoding.fr/)

## Maquettes

Maquette mobile :

<p align="center">
  <img src="/assets/img/mockup/smartphone.png" alt="Maquette Mobile Reservia">
</p>

Maquette desktop :

<p align="center">
  <img src="/assets/img/mockup/desktop.png" alt="Maquette Desktop Reservia">
</p>
