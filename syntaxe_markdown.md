Tableau
----------

Pour créer des tableaux il faut commencer et terminer chaque colonne par “ | ”,et pour les lignes elles se feront automatiquement à chaque passage à la ligne. 

|Entête | de | tableau|
|-------|:----:|--------:|
|contenu |du | tableau|



    |Entête | de | tableau|
    |-------|:----:|--------:|
    |contenu |du | tableau|
De base le texte est aligné à gauche.Pour centrer le texte d’une colonne il faut rajouter “:” de chaque côté de la séparation servant a souligné les entêtes de colonnes (exemple: “ :-----:”).Pour qu’il soit aligné à droite il faut rajouter les “:” uniquement à la fin(exemple: “ ------:”) . Les emphases sur le textes comme italique ou gras fonctionnent aussi dans le tableau.

Bloc de citation
--------------------

On peut aussi mettre du texte en citation en mettant “> ” en début de ligne. Le texte se suivra même si vous changez de ligne dans le markdown .

> être une citation ou ne pas être une citation

exemple :

    > être une citation ou ne pas être une citation
    
    
Mettre du code HTML 
-----------------------------

Markdown offre aussi la possibilité de mettre directement du code html.Mais attention dans  le code HTML les “balises” markdown ne fonctionnent pas , il faut donc , à l'intérieur de balises HTML , utilisé des balises HTML pour mettre de l’emphase sur le texte (exemple: <em> tags</em>).

    <dl>
        <dt><em>Ca à l’air pratique le Markdown:</em></dt>
        <dd>oui c’est pas faut</dd>
    </dl>


<dl>
    <dt><em>Ca à l’air pratique le Markdown:</em></dt>
    <dd>oui c’est pas faut</dd>
</dl>

Lignes horizontales
-------------------------

Il y a trois solutions pour créer une séparation horizontale mais qui utilisent la meme méthode à savoir il faut écrire sur une ligne vierge 3 fois soit “-” soit “*” ou “_”.

---

Hyphens

***

Asterisks

___

Underscores

Passage à la ligne 
------------------------

Pour faire un passage à la ligne en MD ,il faut appuyer deux fois sur la **barre espace** avant d’appuyer sur ** Enter ** de revenir à la ligne sans changer de paragraphe . Pour changer de paragraphe il faudra alors appuyer deux fois sur **Enter**. 


<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>