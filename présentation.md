
# Le Markdown

Markdown est un langage de balisage léger créé en 2004 par [John Gruber](https://fr.wikipedia.org/wiki/John_Gruber) avec [Aaron Swartz](https://fr.wikipedia.org/wiki/Aaron_Swartz). Son but est d'offrir une syntaxe facile à lire et à écrire. Un document balisé par Markdown peut être lu en l'état sans donner l’impression d'avoir été balisé ou formaté par des instructions particulières.

## Table des matières
1. [Introduction](../master/README.md)
2. [Présentation rapide de Markdown](../master/intro.md#présentation-rapide-de-markdown)
3. [Son évolution](#son-évolution)
4. [Syntaxe](../master/syntaxe_markdown.md#syntaxe)
    - [Retours à la ligne](../master/syntaxe_markdown.md#retours-à-la-ligne)
    - [Titres](../master/syntaxe_markdown.md#titres)
    - [Emphases](../master/syntaxe_markdown.md#emphases)
    - [Listes](../master/syntaxe_markdown.md#listes)
    - [Liens](../master/syntaxe_markdown.md#liens)
    - [Images](../master/syntaxe_markdown.md#images)
    - [Extraits de code](../master/syntaxe_markdown.md#extraits-de-code)
    - [Tableau](../master/syntaxe_markdown.md#tableau)
    - [Bloc de citation](../master/syntaxe_markdown.md#bloc-de-citation)
    - [Mettre du code HTML](../master/syntaxe_markdown.md#mettre-du-code-html)
    - [Lignes horizontales](../master/syntaxe_markdown.md#lignes-horizontales)

## Son évolution

Depuis sa création originelle par Gruber, Markdown n'a pas connu d'évolution notoire de la part de ses auteurs. De plus, ce format n'a jamais été formellement standardisé.

Dès le départ, Gruber a écrit un script Perl pour convertir du texte markdown en XHTML. C’est tout l’intérêt du système : éditer un fichier texte simple avec quelques caractères spéciaux supplémentaires, puis le faire passer dans un script qui va l’enrichir des balises requises pour l’afficher avec sa mise en forme dans le navigateur.

Un certain nombre de variantes ont donc été développées par d'autres, afin de pallier ce qui a été perçu comme des limitations inhérentes à une syntaxe très simplifiée.

Ainsi, de nombreuses extensions et “extras” sont venues se greffer au projet originel. Le projet initial avec sa documentation est sur [daringfireball](http://daringfireball.net/projects/markdown), blog créé par Gruber lui-même.

À titre d'exemples, on pourra citer [MultiMarkdown](https://fr.wikipedia.org/wiki/MultiMarkdown) et [GitHub Flavored Markdown](https://github.github.com/gfm/). Ce dernier est utilisé pour les articles et la documentation sur [GitHub](https://fr.wikipedia.org/wiki/GitHub) lui-même, mais a également été largement adopté sur plusieurs éditeurs de texte supportant le format Markdown au niveau de la coloration syntaxique ou de la prévisualisation.

Il existe également des greffons pour de nombreux logiciels populaires, tels que « [Markdown Here](https://markdown-here.com/) » pour Firefox et Chrome, et le système de gestion de contenu WordPress intègre désormais quelques éléments de ce langage nativement depuis la version 4.3.

L'initiative [Common Mark](https://commonmark.org/) vise à pallier le manque de standardisation et les ambiguïtés du format.
