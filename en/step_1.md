## Show and hide sprites on different backdrops

Some sprites should only show on some backdrops when you a creating a book, animation, presentation or game with levels.

**Show and hide sprites on different backdrops**: [See inside](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Click the Stage or `space` key to switch to the `next backdrop`{:class="block3looks"}
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Use `show`{:class="block3looks"} and `hide`{:class="block3looks"} with `when backdrop switches to`{:class="block3events"} to make sprites only show on the backdrops where they belong.

**Beachball:**
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Set the backdrop `when flag clicked`{:class="block3events"} to make sure sprites show or hide correctly on the first page:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** You can also `show`{:class="block3looks"} and `hide`{:class="block3looks"} sprites `when flag clicked`{:class="block3events"}.
