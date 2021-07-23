Wanneer je een boek, animatie, presentatie of game met levels maakt, mogen sommige sprites alleen op bepaalde achtergronden worden weergegeven.

**Sprites op verschillende achtergronden weergeven en verbergen**: [Kijk hier maar eens](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Klik op het werkgebied of druk op de toets <kbd>spatie</kbd> om over te schakelen naar de volgende achtergrond.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Gebruik `verschijn`{:class="block3looks"} en `verdwijn`{:class="block3looks"} blokken met het `wanneer achtergrond verandert naar`{:class="block3events"} blok om sprites alleen op de achtergronden te laten zien waar ze thuishoren.

De **Beachball** sprite:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Stel de `achtergrond`{:class="block3looks"} in `wanneer op de groene vlag wordt geklikt`{:class="block3events"} om ervoor te zorgen dat sprites correct worden weergegeven of verborgen op de eerste achtergrond:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** You can also make sprites `show`{:class="block3looks"} and `hide`{:class="block3looks"} `when green flag clicked`{:class="block3events"}.
