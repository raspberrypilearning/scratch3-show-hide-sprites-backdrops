When you are creating a book, animation, presentation, or game with levels, some sprites should only show on some backdrops.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Use `show`{:class="block3looks"} and `hide`{:class="block3looks"} blocks with the `when backdrop switches to`{:class="block3events"} block to make sprites only show on the backdrops where they belong.

The **Beachball** sprite:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Set the `backdrop`{:class="block3looks"} `when green flag clicked`{:class="block3events"} to make sure that sprites show or hide correctly on the first backdrop:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** You can also make sprites `show`{:class="block3looks"} and `hide`{:class="block3looks"} `when green flag clicked`{:class="block3events"}.
