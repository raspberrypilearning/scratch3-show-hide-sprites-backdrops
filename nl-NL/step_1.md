Wanneer je een boek, animatie, presentatie of game met levels maakt, mogen sommige sprites alleen op bepaalde achtergronden worden weergegeven.

**Sprites op verschillende achtergronden weergeven en verbergen**: [Kijk hier maar eens](https://scratch.mit.edu/projects/499876704/editor){:target="_ blank"}
Klik op het werkgebied of druk op de toets <kbd>spatie</kbd> om over te schakelen naar de `volgende achtergrond`{:class="block3looks"}.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Gebruik `verschijn`{:class="block3looks"} en `verdwijn`{:class="block3looks"} blokken met het `verander achtergrond naar`{:class="block3events"} blok om sprites alleen op de achtergronden te laten zien waar ze thuishoren.

**Strandbal:**
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Stel de `achtergrond`{:class="block3looks"} in met `wanneer op de groene vlag wordt geklikt`{:class="block3events"} om ervoor te zorgen dat sprites correct worden weergegeven of verborgen op de eerste achtergrond:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** Je kunt ook sprites laten `verschijnen`{:class="block3looks"} en `verdwijnen`{:class="block3looks"} `wanneer op de groene vlag wordt geklikt`{:class="block3events"}.
