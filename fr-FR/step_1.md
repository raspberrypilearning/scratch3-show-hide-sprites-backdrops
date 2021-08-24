Lorsque tu crées un livre, une animation, une présentation ou un jeu avec des niveaux, certains sprites ne doivent apparaître que sur certains arrière-plans.

**Afficher et masquer les sprites sur différents arrière-plans** : [Voir à l'intérieur](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Clique sur la scène ou appuie sur la touche <kbd>Espace</kbd> pour passer à l' arrière-plan suivant.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Utilise les blocs `montrer`{:class="block3looks"} et `cacher`{:class="block3looks"} avec le bloc `quand l'arrière-plan bascule sur`{:class="block3events"} pour que les sprites ne s'affichent que sur les arrière-plans où ils appartiennent.

Le sprite **Beachball**:
```blocks3
quand l'arrière-plan bascule sur [Beach Rio v]
montrer

quand l'arrière-plan bascule sur [Soccer 2 v]
cacher
```

Définis l'`arrière-plan`{:class="block3looks"} `quand le drapeau vert est cliqué`{:class="block3events"} pour t'assurer que les sprites s'affichent ou se masquent correctement sur le premier arrière-plan :

```blocks3
when green flag clicked
basculer sur l'arrière-plan [Beach Rio v]
```

**Astuce :** Tu peux également faire en sorte que les sprites `montrent`{:class="block3looks"} et `masquent`{:class="block3looks"} `lorsque le drapeau vert est cliqué`{:class="block3events"}.
