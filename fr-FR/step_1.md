Lorsque tu crées un livre, une animation, une présentation ou un jeu avec des niveaux, certains sprites ne doivent apparaître que sur certains arrière-plans.

**Afficher et masquer les sprites sur différents arrière-plans** : [Voir à l'intérieur](https://scratch.mit.edu/projects/499876704/editor){:target="_ blank"}
Clique sur la scène ou appuie sur la touche <kbd>Espace</kbd> pour passer à l' `arrière-plan suivant`{:class="block3looks"}.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Utilise les blocs `montrer`{:class="block3looks"} et `cacher`{:class="block3looks"} avec le bloc `quand l'arrière-plan bascule sur`{:class="block3events"} pour que les sprites ne s'affichent que sur les arrière-plans où ils appartiennent.

**Ballon de plage :**
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Définis l'`arrière-plan`{:class="block3looks"} `quand le drapeau vert est cliqué`{:class="block3events"} pour t'assurer que les sprites s'affichent ou se masquent correctement sur le premier arrière-plan :

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Astuce :** tu peux également `montrer`{:class="block3looks"} et `cacher`{:class="block3looks"} des sprites `quand le drapeau vert est cliqué`{:class="block3events"}.
