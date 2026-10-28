# Exercice 2 - Installer Apache

Ce document est joint au fichier installer-apache.html pour epliciter mes choix de structure.

## Justification des éléments du squelette

`<!DOCTYPE html> `Permet de déclarer le type de document. dans le HTML5, pas besoin de rajouter autre chose.

`<html lang="fr">`déclare le début du document HTML et se referme à la toute fin avec `</html>`. 

`<head></head>` contient les caractéristiques du document HTML. Ces informations là ne sont pas visibles dans la page.

`<meta charset="UTF-8">` permet de déclarer l'encodage des caractères. UTF-8 spécifiquement inclut les accents et caractères spéciaux.  

`<title>Page d'exemple HTML</title>` indique le titre du document. Il apparaît dans le titre de l'onglet, et dans le résultat de recherche Google.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">` : Cette déclaration permet à la page de s'adapter à la largeur de son viewport, de sa fenêtre. 

`<body></body>` est la balise qui contient le corps de page, son contenu visible.

`<h1></h1>` est le titre de niveau 1, le titre principal de la page, et qui sera interprété comme tel par les indexeurs de moteurs de recherche.

`<h2></h2>` est le titre de niveau 2, hiérarchisant ce titre par rapport à celui de niveau 1. En termes de sémantique, ça permet aux moteurs de recherche de mieux comprendre la hiérarchie du contenu de la page.

`<p></p>` est un paragraphe de texte. 

`<ol></ol>` déclare une liste numérotée. Les balises `<li></li>` à l'intérieur déclarent les éléments ordonnés de cette liste.

`<ul></ul>` déclare une liste à puces, non ordonnée. On utilise les `<li></li>` de la même manière que dans `<ol></ol>`. 