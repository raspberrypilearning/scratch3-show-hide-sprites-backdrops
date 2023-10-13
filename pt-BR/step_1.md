Quando você está criando um livro, animação, apresentação ou jogo com níveis, alguns atores devem aparecer apenas em alguns cenários.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Use os blocos `mostrar`{:class="block3looks"} e `esconder`{:class="block3looks"} com o bloco `quando o cenário mudar para`{:class="block3events"} para fazer os atores aparecerem somente nos cenários aos quais eles pertencem.

O ator **Bola de praia**:
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

**Dica:** Você também pode fazer os atores se `mostrarem`{:class="block3looks"} e se `esconderem`{:class="block3looks"} `quando a bandeira verde for clicada`{:class="block3events"}.
