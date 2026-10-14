# Exercices HTML

## Exercice A

```html
<html>
<body>
  <head> <!--la balise <head> de doit pas être dans <body>. Le <head> ne sera pas toujours bien interprété selon le navigateur et le document ne sera pas validé par le W3C.-->
    <meta charset="UTF-8">
    <title>Réseau du BTS SIO</title>
  </head>
  <h1>Bienvenue sur ma page</h1>
  <p>Je prépare un BTS SIO option SISR.<p> <!--La balise <p> n'est pas fermée correctement, la balise de fermeture doit s'écrire </p>. Laissé comme ça, la suite du HTML seera considérée aussi comme un paragraphe.-->
</body>
<!DOCTYPE html> <!--Le DOCTYPE doit être déclaré en début de document. Il ne sera pas validé par le W3C ainsi.-->
</html>
```

## Exercice B

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UFT-8"> <!--Le charset appelé s'appelle "UTF-8" et non "UFT-8", si il est mal déclaré, les caractères seront mal interprétés et le texte aura des symboles bizarres-->
    <!--Il manque la balise <title>-->
</head>
<body>
  <h1>Ma page</h1>
  <p>Élève de première année</p>
</html> <!--La balise <html> doit être fermée après <body> car elle marque le début et la fin du document. Le document HTML ne sera pas valide ainsi.-->
</body>
```

