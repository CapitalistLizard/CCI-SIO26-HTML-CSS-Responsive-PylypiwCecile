# Les règles CSS

## 1. Recherche autonome et formalisation

Une règle CSS est une propriété qui s'applique à un élément HTML pour en modifier son apparence et sa mise en page. Elle est appelée dans la balise `<head>` avec la balise suivante : `<link rel ="stylesheet" href="">` . Le href doit mener à un fichier de feuille de style en `.css`. Autrement, il est aussi possible d'insérer du code CSS directement dans le `<head>` avec la balise `<style>`, ou bien d'attribuer du CSS à une balise en particulier avec l'attribut `style`, mais c'est moins pratique qu'un fichier à part.

`p` est un sélecteur désignant un paragraphe `<p>`. En utilisant ce sélecteur, le style défini s'appliquera à tous les paragraphes `<p>` du fichier HTML où la feuille de style est appelée.

On relie un fichier CSS à une page HTML en utilisant la balise `<link rel ="stylesheet" href="">`. Le chemin d'accès dans le fichier est défini dans l'attribut `href`.

On dit que la feuille de style "cascade" car c'est l'ordre et la manière dont les attributs sont appliqués. l'algorithme de cascade CSS va par défaut appliquer les styles de l'élément parent sur l'élément enfant et ainsi de suite, et lire les attributs du haut vers le bas du fichier. 

Le navigateur va appliquer le dernier attribut déclaré pour un même élément.
