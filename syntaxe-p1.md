# Syntaxe

Le Markdown a une syntaxe spécifique pour créer ses différents éléments. Tout ce qui ne correspond pas à ces éléments sera considéré comme du simple texte.

## Table des matières

1. [Introduction](../blob/master/README.md)
2. [Présentation rapide de Markdown](../blob/master/presentation.md#presentation-rapide-de-markdown)
3. [Son évolution](../blob/master/presentation.md#son-evolution)
4. [Syntaxe](#syntaxe)
    - [Retours à la ligne](#retours-a-la-ligne)
    - [Titres](#titres)
    - [Emphases](#emphases)
    - [Listes](#listes)
    - [Liens](#liens)
    - [Images](#images)
    - [Extraits de code](#extraits-de-code)

## Retours à la ligne
Par défaut, Markdown ignore les retours à la ligne du code et mets tout le texte à la suite.  
Pour faire un simple retour à la ligne, il est possible de laisser deux espaces en fin de ligne, avant son retour à la ligne dans le code.

Pour créer un nouveau paragraphe, il suffit de faire un double retour à la ligne dans le code.

```markdown
Par défaut, Markdown ignore les retours à la ligne du code et mets tout le texte à la suite.  
Pour faire un simple retour à la ligne, il est possible de laisser deux espaces en fin de ligne, avant son retour à la ligne dans le code.

Pour créer un nouveau paragraphe, il suffit de faire un double retour à la ligne dans le code.
```

## Titres

Pour créer des titres, il suffit d'écrire un # par niveau de titre souhaité.

# H1
## H2
### H3
#### H4
##### H5
###### H6

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Pour les titres de premier et second niveau, il est également possible d'utiliser une syntaxe soulignée.

Alt-H1
======

Alt-H2
------

```markdown
Alt-H1
======

Alt-H2
------
```

## Emphases

Pour mettre du texte en italique, il suffit d'entourer le contenu à mettre en évidence par des *astérisques* ou des _underscores_.  
Pour mettre du texte en gras, il faut l'entourer par des doubles **astérisques** ou des __doubles underscores__.  
Il est possible de combiner le gras et l'italique en **utilisant les deux méthodes _simultanément_**.  
On peut ~~barer du contenu~~ en l'entourant de deux tildes.

```markdown
Pour mettre du texte en italique, il suffit d'entourer le contenu à mettre en évidence par des *astérisques* ou des _underscores_.  
Pour mettre du texte en gras, il faut l'entourer par des doubles **astérisques** ou des __doubles underscores__.  
Il est possible de combiner le gras et l'italique en **utilisant les deux méthodes _simultanément_**.  
On peut ~~barer du contenu~~ en l'entourant de deux tildes.
```

## Listes

Pour créer des listes ordonnées, il suffit d'utiliser des chiffres devant chaque élément de la liste.  
Notez que seul le fait que ce soit un chiffre est important, pas qu'ils soient dans l'ordre.

1. Premier élément de liste
7. Second élément de liste
5. Troisième élément de liste

```markdown
1. Premier élément de liste
7. Second élément de liste
5. Troisième élément de liste
```

Pour créer des listes non-ordonnées, on peut utiliser des tirets, des astérisques ou des plus.

* Premier élément de liste
- Second élément de liste
+ Troisième élément de liste

```markdown
* Premier élément de liste
- Second élément de liste
+ Troisième élément de liste
```

Pour créer des listes imbriquées, il suffit de les disposer avec au moins 2 espaces devant les éléments de la sous-liste.

* Premier élément de liste
- Second élément de liste
  1. Premier élément de sous-liste
  2. Second élément de sous-liste
+ Troisième élément de liste

```markdown
* Premier élément de liste
- Second élément de liste
  1. Premier élément de sous-liste
  2. Second élément de sous-liste
+ Troisième élément de liste
```

## Liens

Il y a plusieurs moyens de créer un lien.  
Soit on place entre parenthèses l'URL du lien et on le fait précéder du texte qui doit servir de lien entre crochets, soit on utilise des références entre crochets au lieu de l'URL pour définir ces liens plus tard.  
Toute URL complète ou placée entre crochets sera également traduite en lien.

[Ceci est un lien basique](http://github.com)  
[Ceci est un lien avec un titre](http://github.com "Github")  
[Ceci est un lien avec référence][texte de reference]    
[Ceci est un lien relatif](../blob/master/README.md)  
http://github.com  
<http://github.com>  

[texte de reference]: http://github.com

```markdown
[Ceci est un lien basique](http://github.com)  
[Ceci est un lien avec un titre](http://github.com "Github")  
[Ceci est un lien avec référence][texte de reference]    
[Ceci est un lien relatif](../blob/master/README.md)  
http://github.com  
<http://github.com>  

[texte de reference]: http://github.com
```

## Images

Vous pouvez inclure des images de la même manière que vous créez des liens, à une exception près : vous commencez par un point d'exclamation, puis vous mettez le texte alternatif entre crochets et vous le faites suivre de l'URL de votre image entre parenthèse.  
Comme pour les liens, vous pouvez ajouter des titres à vos images (visibles au survol) en les ajoutant entre guillemets à la suite de votre URL, dans les parenthèses.

![logo de BeCode](https://www.becode.org/register/assets/images/logo_Becode.png "texte au survol")  
![logo de BeCode][reference]

[reference]: https://www.becode.org/register/assets/images/logo_Becode.png

```markdown
![logo de BeCode](https://www.becode.org/register/assets/images/logo_Becode.png)  
![logo de BeCode][reference]

[reference]: https://www.becode.org/register/assets/images/logo_Becode.png
```

## Extraits de code

Pour afficher un extrait de code en ligne, on peut l'entourer d'accents graves. Pour créer des blocs de code, il suffit d'entourer le code de 3 accents graves avant et après le bloc.

Ceci est `<span>du code en ligne</span>`. Pratique, non ?  
Ceci est un bloc
```
<p>Comme vous pouvez le voir</p>
<p>Tout ce qui se trouve ici est bien dans un bloc</p>
<p>Et pas en ligne</p>
```
de code.

Par défaut, la coloration syntaxique ne fait pas partie de Markdown. Mais certains interpréteurs comme celui de GitHub supportent la coloration syntaxique pour peu qu'on spécifie de quel langage il s'agit (s'il est reconnu par l'interpréteur, bien sûr).  
Il suffit alors de spécifier ce langage à la suite des trois accents graves d'ouverture de bloc de code. La coloration syntaxique ne fonctionne que pour les blocs de code et pas le texte en ligne.

```HTML
<p>Comme vous pouvez le voir</p>
<p>Tout ce qui se trouve ici est bien dans un bloc</p>
<p>Et pas en ligne</p>
```

```javascript
var s = "Coloration syntaxique en Javascript";
alert(s);
```

```python
s = "Coloration syntaxique en Python"
print s
```
