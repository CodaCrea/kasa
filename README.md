# Kasa 🏡
[Voir le site](https://devveric.github.io/kasa)

## Description :
Ceci est un projet réalisé dans le cadre du programme de formation Développeur Front-end JavaScript React chez OpenClassrooms

Implémentez le front end d'une application de location de logements. Mettez en place des composants avec React et les routes de l'application avec React Router.

## Compétences évaluées :
1. Créer des composants avec React
2. Développer les routes d'une application web avec React Router
3. Initialiser une application web avec un framework

### Situation (fictive) du projet :
Développeur freelance, missionné en tant que Développeur Front-end, une entreprise spécialisée dans la location d’appartements entre particuliers depuis près de 10 ans. .

L’entreprise souhaite faire une refonte totale de leur site pour passer à une stack complète en JavaScript avec NodeJS côté Back-end et React côté Front-end.

Mon rôle a été de développer le front-end de l’application, en utilisant les composants React, les routes React Router et en respectant les maquettes Figma.

## Contraintes techniques :
### Outils :
* Create React App.
* React Router.
* L’utilisation de Sass est optionnelle. CSS est à utiliser par défaut.
* Pas de librairie React externe.
### React :
* Structure logique des différents fichiers.
* Découpage en composants modulaires et réutilisables (Un composant par fichier).
* Il est recommandé d’utiliser des composants fonctionnels au lieu des composants classes.
* Utilisation des props entre les composants.
* Utilisation du state dans les composants quand c'est nécessaire.
* Gestion des événements.
* Utiliser les listes autant que possible en itérant dessus (par exemple avec map).
### React Router :
* La logique du routeur est réunie dans un seul fichier.
* Il existe une page par route.
* Les paramètres des routes sont gérés par React Router dans l'URL pour récupérer les informations de chaque logement.
* La page 404 est renvoyée pour chaque route inexistante, ou si une valeur présente dans l’URL ne fait pas partie des données renseignées.
>Général : Le code ne doit pas produire d'erreur ou de warning dans la console.

## Contraintes fonctionnelles :
### Pour le défilement des photos dans la galerie (composant Gallery) :
* Si l'utilisateur se trouve à la première image et qu'il clique sur "précédent", la galerie affiche la dernière image.
* Inversement, quand l'image affichée est la dernière de la galerie, si l'utilisateur clique sur "suivant", la galerie affiche la première image.
* S'il n'y a qu'une seule image, les boutons "suivant" et "précédent" n'apparaissent pas.
>La galerie doit toujours rester de la même hauteur, celle indiquée sur la maquette Figma.
Les images seront donc coupées et centrées dans le cadre de l’image.
### Collapse :
Par défaut, les Collapse sont fermés à l'initialisation de la page.
Si le Collapse est ouvert, le clic de l'utilisateur permet de le fermer.
Inversement, si le Collapse est fermé, un clic permet de l'ouvrir.

## Installation :
### Cloner le repository :
git clone https://github.com/devveric/Kasa.git
* Installer toutes les dépendances pour le front-end :
npm install ou yarn
* Lancer le front-end :
npm start ou yarn start
>Le front-end sera lancé à l'URL: http://localhost:3000/Kasa/.

## Développé avec :
* Visual Studio Code - Éditeur de texte
* CSS - Aucun frameworks
* React 18 - Bibliothèque JavaScript libre développée par Facebook
* Create React App - Boîte à outils créée par Facebook, qui est la référence pour initier un projet React
* React Router V6 - Bibliothèque de routage pour React
* GitHub - Outil de gestion de versions
* GitHub Pages - Outil d’hébergement
* Auteur : BILLON-TYRARD Eric
##### Maquette figma :
https://www.figma.com/file/bAnXDNqRKCRRP8mY2gcb5p/UI-Design-Kasa-FR?node-id=3-0
