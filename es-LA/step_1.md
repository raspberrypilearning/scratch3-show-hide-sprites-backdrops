Cuando creas un libro, una animación, una presentación o un juego con niveles, algunos objetos solo deben mostrarse en algunos fondos.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

Usa bloques `mostrar`{:class="block3looks"} y `esconder`{:class="block3looks"} con el bloque `cuando el fondo cambie a`{:class="block3events"} para que los objetos solo se muestren en los fondos donde pertenecen.

El objeto **Beachball**:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Establece el `fondo`{:class="block3looks"} `al presionar la bandera verde`{:class="block3events"} para asegurarte de que los objetos se muestran o esconden correctamente en el primer fondo:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Consejo:** También puedes `mostrar`{:class="block3looks"} y `esconder`{:class="block3looks"} objetos `al presionar la bandera verde`{:class="block3events"}.
