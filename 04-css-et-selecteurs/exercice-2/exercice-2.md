# Exercice 2

Voici une liste des sélecteurs utilisés ainsi que leur importance et utilité :

- Pour sélectionner tous les paragraphes du fichier, j'ai simplement choisi le sélecteur `p`, désignant toutes les balises `<p>` 
- Les classes sont des attributs pouvant être ajoutés aux balises pour permettre une sélection CSS plus ciblée. On peut réutiliser plusieurs fois la même classe dans le document. Sélectionner une classe doit toujours commencer par un point, ici `.important`.
- Les identifiants doivent être uniques, contrairement aux classes. Ils permettent de sélectionner un élément unique dans le HTML. On le sélectionne avec un dièse, ici, `#entete`.
- Pour sélectionner plusieurs éléments à la fois, on les sépare d'une virgule avec un espace. Pour sélectionner les deux titres h1 et h2, on écrit ainsi : `h1, h2`.
- Ici, la classe "actif" n'est présente qu'une fois dans le document HTML. On la sélectionne donc avec `.actif`.
- Pour sélectionner uniquement la balise `<p>` se trouvant dans le footer, on fait une sélection de tous les `<p>` enfants de `<footer>` avec un espace, de cette manière : `footer p` 
- Pareil que pour `footer p`, on sélectionne les éléments `li` descendants de l'élément portant l'ID `#agenda`. l'espace sélectionne tous les descendants, donc ça fonctionne même si il y a un autre conteneur dans l'arborescence. donc `#agenda li`. 
- Pour sélectionner un élément spécifique portant deux classes, on écrit les deux classes à la suite dans espace, ici `.important.rappel`.