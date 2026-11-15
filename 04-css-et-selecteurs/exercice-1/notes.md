# Exercice 1

La couleur de `<h1>` est appliquée à l'aide de l'attribut CSS `color`, sur le fichier CSS, dans la balise `<style>` présente dans le `<head>` et dans l'attribut `style` de la balise `<h1>` directement. L'attribut `style` dans la balise `<h1>` a la priorité sur les autres attributs déclarés ailleurs, quand je mets par exemple un `color: red;` dans le fichier CSS et un `color: green;` dans la balise `<style>` , le titre reste bleu foncé. 

En ce qui concerne le CSS appelé via la balise `<link>` et via la balise `<style>`, leur priorité dépendra de ce qui est appelé en dernier dans le fichier HTML.