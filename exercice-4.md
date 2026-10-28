# Exercice 4 - page sur la commande "ping"

Cet exercice consiste à rédiger soi-même une page HTML suivant un brief.

## Justification de la hiérarchie des titres et listes

Le titre principal de la page "La commande ping" est dans une balise `<h1>`. Ce titre permet de titrer la page et donner son sujet. Les titres `<h2>` sont eux utilisés pour séparer les différentes sous-parties du document. Les titres `<h3>` sont eux utilisés comme sous-parties d'un titre `<h2>` comme dans "Utilisation pas à pas".

Concernant les listes, elles se présentent sous forme d'éléments `<li>` contenus dans des balises `ul` ou `<ol>`. La balise `<ul>` exprime une liste à points d'éléments non ordonnés, et la balise `<ol>` exprime une liste ordonnée avec des chiffres.

## La différence entre le titre de l'onglet et le titre affiché dans la page

Le titre de l'onglet est caractérisé par la balise `<title>`. Il désigne le titre du document au complet et son nom dans le référencement. Le titre affiché dans la page est lui indiqué dans la balise `<h1>`. 

## La différence de rôle entre HTML, CSS et JavaScript

HTML est le langage permettant de baliser une page web pour en décrire la structure et la sémantique. Il permet d'avoir un document lisible par un navigateur web et indexable par les moteurs de recherche. 

CSS est le langage permettant la définition de l'aspect visuel des pages web. On peut s'en servir pour définir la couleur des éléments, la police des textes, la mise en page, le comportement des éléments selon le support et la largeur de l'écran sur lequel on consulte le site, et on peut même faire des animations.

Javascript est le véritable langage de programmation des pages web côté client. Il permet de coder des pages web dynamiques et rajouter de l'interactivité.

## Ce que fait le navigateur entre la réception du fichier et l'affichage

Lors de la lecture du HTML, le navigateur web décompose le code de haut en bas en DOM (Document Object Model), une arborescence de la page. Il crée aussi le CSSOM à partir des feuilles de style (un navigateur en propose toujours une par défaut, même si nous n'en mettons pas.). A partir de là, le navigateur crée l'arbre de rendu, ne contenant que les éléments visibles. Les éléments en `display: none` ne seront pas rendus, alors que ceux en `visibility: hidden` si. L'arbre de rendu permet au navigateur de calculer la taille et la position des éléments à afficher. 
Après cela, le navigateur passe à l'étape du "paint" où il va afficher les éléments grâce aux pixels, et au "compositiong" où il organise les éléments du site en couches (ou layers), pouvant être animées indépendamment. C'est là que le processeur graphique du navigateur peut être sollicité, pour la transparence ou l'animation par exemple.