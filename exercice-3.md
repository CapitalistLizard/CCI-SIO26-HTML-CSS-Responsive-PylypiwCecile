# Phase 5 - Exercice 3

Ici nous allons corriger les erreurs de hiérarchie et de sémantique dans un document HTML.

## Support - Extraits

### Extrait A

```html
<h1>Les réseaux</h1>
<h3>Le modèle OSI</h3>
<h3>Le modèle TCP/IP</h3>
```

Ici, la hiérarchie des titres n'est pas respectée : on passe directement du `<h1>` au `<h3>`. ça peut perturber l'indexation et le référencement du site.

### Extrait B

```html
<h1>Guide du technicien</h1>
<h1>Installation</h1>
<h1>Configuration</h1>
```

Cet extrait utilise 3 titres `<h1>` à la suite, alors qu'un titre `<h1>` doit au mieux être utilisé une fois pour titrer toute la page. En plus dans cet exemple, les titres "installation" et "configuration" devraient être des titres `<h2>` car ils séparent les sujets du Guide du Technicien.

### Extrait C

```html
<h2>Sauvegardes</h2>
<h4>Sauvegarde complète</h4>
<h4>Sauvegarde incrémentale</h4>
<h1>Conclusion</h1>
```

La hiérarchie des titres n'a aucune logique. Les robots indexeurs ne vont rien comprendre à cette page et son classement SEO risque d'être compromis.

### Extrait D 

```html
<h1>Serveur DNS</h1>
<p><h2>Rôle du serveur</h2></p>
<p>Il traduit les noms de domaine en adresses IP.</p>
```

Ici, le titre `<h2>` se trouve dans une balise `<p>`. Ce n'est pas une bonne pratique, la page ne passera pas la validation W3C et la balise `<p>` indiquant un paragraphe, un titre n'a rien à faire dedans.

### Extrait E

```html
<h1>Procédure de mise à jour</h1>
<h2>Attention : ne pas éteindre le serveur pendant la mise à jour</h2>
<ol>
  <li>Lancer la mise à jour.</li>
  <li>Attendre la fin du traitement.</li>
</ol>
```

Le texte contenu dans la balise `<h2>` n'est pas supposé être un titre. Il aurait mieux fallu le mettre dans un `<p>`.

## Support - situations

| Situation                                                    | Code                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Présenter les étapes à suivre pour configurer une adresse IP statique. | `<ol><li>Ouvrez les paramètres réseau.</li><li>Désactivez le DHCP.</li><li>Saisissez l’adresse, le masque et la passerelle.</li><li>Validez et testez.</li></ol>` |
| Énumérer les ports courants d'un serveur web (80, 443, 22, 25), sans ordre particulier. | `<ul><li>Port 80</li><li>Port 443</li><li>Port 22</li><li>Port 25</li></ul>` |
| Mettre en évidence l'avertissement « Ne jamais exécuter cette commande en production ». | `<p><strong>Ne jamais exécuter cette commande en production</strong></p>` |
| Insister sur le mot « avant » dans la phrase « Sauvegardez avant de modifier ». | `<p>Sauvegardez <b>avant</b> de modifier</p>`                |

