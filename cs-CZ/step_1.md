Když vytváříte knihu, animaci, prezentaci nebo hru s úrovněmi, některé postavy by se měly zobrazovat pouze na některých pozadích.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Použijte `ukaž se`{:class="block3looks"} a `skryj se`{:class="block3looks"} bloky s `po změně pozadí na`{:class="block3events"}, aby se postavy zobrazovaly pouze na pozadí kam patří.

Postava **volejbalový míč**:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Nastavte `pozadí`{:class="block3looks"} `při kliknutí na zelenou vlajku`{:class="block3events"}, abyste se ujistili, že se postava zobrazí nebo skryje správně na prvním pozadí:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** Můžete také nastavit postavy tak, aby se `zobrazily`{:class="block3looks"} nebo `skryly`{:class="block3looks"} `při kliknutí na zelenou vlajku`{:class="block3events"}.
