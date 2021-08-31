レベルが設定されてるゲームや、スライド、アニメーション、本などを作る時、背景でスプライトの表示を切り替たくなります。

**背景でスプライトの表示を切り替える**: [なかをみる](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
ステージをクリックするか<kbd>スペースキー</kbd>を押すことで、次の背景に変わります。
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

それぞれの背景でスプライトを切り替えるには、`背景が...になったとき`{:class="block3events"}イベントと一緒に、`表示する`{:class="block3looks"}と`隠す`{:class="block3looks"}ブロックを使います。

**ビーチボール** スプライト：
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

`緑の旗が押されとき`{:class="block3events"}イベントの`背景を...にする`{:class="block3looks"}で設定した背景で、スプライトの表示が正しく出来てるかを確認しましょう。

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**ヒント：**`緑の旗が押されたとき`{：class = "block3events"}`表示する` {：class = "block3looks"}や `隠す`{：class = "block3looks"}ことができます。
