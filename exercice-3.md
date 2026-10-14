# Exercice 3

## Page de présentation d'un service informatique

```html
<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Service informatique - lycée</title>
    </head>
    <body>
        <!--Etudiant à l'origine de cette page : Cécile Pylypiw-Staub-->
        <h1>Bonjour.</h1>
        <p>
            Le service informatique du lycée Saint-Jean-la-Mayonnaise est chargé de maintenir le parc informatique composé de 65 PC équipés de Windows 98, 28 minitels, 12 imprimantes et 1 machine à café. C'est beaucoup de travail, c'est pour cela que ce site n'a pas de page de contact.
        </p>
        <h2>Horaires d'ouverture</h2>
        <ul>
            <li>Lundi : fermé</li>
            <li>Mardi : fermé</li>
            <li>Mercredi : 11h30 - 11h45</li>
            <li>Jeudi : fermé</li>
            <li>Vendredi : fermé</li>
        </ul>
    </body>
</html>
```

### Explications

- Pour déclarer le fait que le document est en HTML5, il faut indiquer le !DOCTYPE en tout début de document. La langue française est indiquée par l'attribut "lang" du tag <html>, et l'encodage par l'attribut "charset" du tag "meta".
- Le titre d'onglet est indiqué par la balise <title> du <head>.
- Les titres visibles utilisent les balises h1 et h2. 
- Les paragraphes utilisent les balises p. Pour les horaires d'ouverture, j'ai mis une liste à puces avec les balises <!--<li> imbriquées dans un <ul>-->.
- Pour que la page s'adapte à la largeur du viewport, selon si on dimensionne la fenêtre du navigateur ou si on consulte le site sur un téléphone, il faut ajouter une autre balise <meta> dans le <head> avec les attributs suivants : name="viewport" content="width=device-width, initial-scale=1.0".
- Les commentaires en HTML sont indiqués entre <!-- --> 
- L'indentation du code est facilitée par des logiciels comme VSCode ou VSCodium, mais il ne faut pas lésiner sur les sauts de ligne et les tabulations. 
