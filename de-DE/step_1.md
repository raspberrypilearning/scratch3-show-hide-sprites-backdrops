Wenn du ein Buch, eine Animation, eine Präsentation oder ein Spiel mit Level erstellst, sollten einige Figuren nur vor bestimmten Hintergründen angezeigt werden.
**Figuren auf verschiedenen Hintergründen ein- und ausblenden**: [Schau hinein](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Klicke auf die Bühne oder drücke die <kbd>Leertaste</kbd>, um zum nächsten Hintergrund zu wechseln.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Verwende die Blöcke `zeige dich`{:class="block3looks"} und `verstecke dich`{:class="block3looks"} mit dem Block `Wenn das Bühnenbild zu ... wechselt`{:class="block3events"}, damit Figuren nur auf den Hintergründen angezeigt werden, wo sie hingehören.

Die **Beachball** Figur:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Stelle den `Hintergrund`{:class="block3looks"} `ein, wenn auf die grüne Flagge geklickt wird`{:class="block3events"}, um sicherzustellen, dass die Figuren auf dem ersten Hintergrund richtig angezeigt oder ausgeblendet werden:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tipp:** Du kannst Figuren auch `zeigen`{:class="block3looks"} und `verstecken`{:class="block3looks"} `, wenn auf die grüne Flagge geklickt wird`{:class="block3events"}.
