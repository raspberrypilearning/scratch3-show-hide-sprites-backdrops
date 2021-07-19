Quando estás a criar um livro, animação, apresentação ou um jogo com níveis, alguns atores devem aparecer apenas em alguns cenários.

**Show and hide sprites on different backdrops**: [See inside](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Click on the Stage or press the <kbd>Space</kbd> key to switch to the next backdrop.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Use os blocos `mostrar`{:class="block3looks"} and `esconder`{:class="block3looks"} com o bloco `quando o cenário mudar para`{:class="block3events"} para fazer os atores aparecerem somente nos cenários aos quais eles pertencem.

The **Beachball** sprite:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Configure o `cenário`{:class="block3looks"} `quando a bandeira verde for clicada`{:class="block3events"} para ter certeza que os atores sejam mostrados ou escondidos corretamente no primeiro cenário:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** You can also make sprites `show`{:class="block3looks"} and `hide`{:class="block3looks"} `when green flag clicked`{:class="block3events"}.
