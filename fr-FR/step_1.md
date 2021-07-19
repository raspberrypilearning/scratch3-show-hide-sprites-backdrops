Lorsque tu crées un livre, une animation, une présentation ou un jeu avec des niveaux, certains sprites ne doivent apparaître que sur certains arrière-plans.

**Show and hide sprites on different backdrops**: [See inside](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Click on the Stage or press the <kbd>Space</kbd> key to switch to the next backdrop.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Utilise les blocs `montrer`{:class="block3looks"} et `cacher`{:class="block3looks"} avec le bloc `quand l'arrière-plan bascule sur`{:class="block3events"} pour que les sprites ne s'affichent que sur les arrière-plans où ils appartiennent.

The **Beachball** sprite:
```blocks3
quand l'arrière-plan bascule sur [Beach Rio v]
montrer

quand l'arrière-plan bascule sur [Soccer 2 v]
cacher
```

Définis l'`arrière-plan`{:class="block3looks"} `quand le drapeau vert est cliqué`{:class="block3events"} pour t'assurer que les sprites s'affichent ou se masquent correctement sur le premier arrière-plan :

```blocks3
quand le drapeau vert est cliqué 
basculer sur l'arrière-plan [Beach Rio v]
```

**Tip:** You can also make sprites `show`{:class="block3looks"} and `hide`{:class="block3looks"} `when green flag clicked`{:class="block3events"}.
