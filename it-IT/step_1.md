Quando crei un libro, un'animazione, una presentazione o un gioco con livelli, alcune immagini dovrebbero essere visualizzate solo su alcuni sfondi.

**Mostra e nascondi le immagini su sfondi diversi**: [Guarda qui](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Fai clic sullo Stage o premi il tasto <kbd>Barra spaziatrice</kbd> per passare allo sfondo successivo.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Usa i blocchi `mostra`{:class="block3looks"} e `nascondi`{:class="block3looks"} con il blocco `quando lo sfondo passa a`{:class="block3events"} per fare in modo che le immagini vengano visualizzate solo sugli sfondi a cui appartengono.

Lo sprite **Beachball**:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Impostare lo `sfondo`{:class="block3looks"} `quando clicchi sulla bandiera verde`{:class="block3events"} per assicurarsi che le immagini si mostrino o si nascondano correttamente sul primo sfondo:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Suggerimento:** Puoi anche `mostrare`{:class="block3looks"} e `nascondere`{:class="block3looks"} le immagini `quando clicchi sulla bandiera verde`{:class="block3events"}.
