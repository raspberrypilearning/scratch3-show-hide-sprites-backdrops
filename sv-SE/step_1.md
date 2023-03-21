När du skapar en bok, animation, presentation eller spel med nivåer bör vissa sprajts bara visas på vissa bakgrunder.

**Visa och dölj sprajts på olika bakgrunder**: [Se inuti](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Klicka på scenen eller tryck på <kbd>blanksteg</kbd> för att växla till nästa bakgrund.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Använd `visa`{:class="block3looks"} och `dölj`{:class="block3looks"} blocken med `när bakgrunden växlar till`{:class="block3events"} blocket för att få sprajts att endast visas på bakgrunderna där de hör hemma.

**Badboll** sprajten:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Ställ in `-bakgrunden`{:class="block3looks"} `när grön flagga klickas`{:class="block3events"} för att se till att sprajts visas eller döljs korrekt på den första bakgrunden:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tips:** Du kan också få sprajts att `visa`{:class="block3looks"} och `dölja`{:class="block3looks"} `när grön flagga klickas`{:class="block3events"}.
