Quando estás a criar um livro, animação, apresentação ou um jogo com níveis, alguns atores devem aparecer apenas em alguns cenários.

**Mostrar e esconder atores em diferentes cenários**: [Veja dentro](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Clique no Palco ou pressione a tecla <kbd>Espaço</kbd> para mudar para o próximo cenário.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Use os blocos `mostrar`{:class="block3looks"} and `esconder`{:class="block3looks"} com o bloco `quando o cenário mudar para`{:class="block3events"} para fazer os atores aparecerem somente nos cenários aos quais eles pertencem.

A **Bola de praia** ator:
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

**Dica:** Também podes fazer atores `mostrar`{:class="block3looks"} e `esconder`{:class="block3looks"} atores `quando a bandeira verde for clicada`{:class="block3events"}.
