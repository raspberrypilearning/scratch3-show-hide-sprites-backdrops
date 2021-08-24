عندما تنشئ كتاب أو رسوم متحركة أو عرض تقديمي أو لعبة بمستويات ، يجب أن تظهر بعض الكائنات على بعض الخلفيات فقط.

**إظهار وإخفاء الكائنات على الخلفيات المختلفة**: [انظر من الداخل](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
انقر على المنصة أو اضغط على مفتاح <kbd>المسافة</kbd> للتبديل إلى الخلفية التالية.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

استخدم كتل `عرض`{:class="block3looks"} و `اخفاء`{:class="block3looks"} مع كتلة `عندما تتبدل الخلفية الى`{:class="block3events"} لجعل الكائنات تظهر فقط على الخلفيات حيث ينتمون.

الكائن **Beachball**:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

أضبط`الخلفية`{:class="block3looks"} `عندما ننقر العلم الأخضر`{:class="block3events"} للتأكد من أن الكائنات المتحركة تظهر أو تختبئ بشكل صحيح على الخلفية الأولى:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**نصيحة:** يمكنك أيضا جعل الكائنات `تظهر`{:class="block3looks"} و `تختفي`{:class="block3looks"} `عند نقر العلم الأخضر`{:class="block3events"}.
