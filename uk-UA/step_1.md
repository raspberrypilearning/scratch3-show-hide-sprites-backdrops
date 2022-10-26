Коли ти створюєш книгу, анімацію, презентацію або гру з рівнями, деякі спрайти повинні відображатися тільки на певних тлах.

**Показувати й приховувати спрайти на різних тлах**: [Переглянути код](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Клацни на сцену або натисни клавішу <kbd>Пробіл</kbd> для зміни тла на наступне.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Використовуй блоки `показати`{:class="block3looks"} та `сховати`{:class="block3looks"} із блоком `коли тло зміниться на`{:class="block3events"}, щоб спрайти відображалися тільки на тих фонах, на яких вони повинні відображатись.

Спрайт **Beachball**:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Встанови блоки `наступне тло`{:class="block3looks"} та `коли зелений прапорець натиснуто`{:class="block3events"}, щоб переконатися, що спрайти правильно показуються або ховаються на першому фоні:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Порада:** Також можна додати спрайти `показати`{:class="block3looks"} та `сховати`{:class="block3looks"} `коли зелений прапорець натиснуто`{:class="block3events"}.
