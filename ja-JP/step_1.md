レベルが設定されてるゲームや、スライド、アニメーション、本などを作る時、背景でスプライトの表示を切り替たくなります。

**Show and hide sprites on different backdrops**: [See inside](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Click on the Stage or press the <kbd>Space</kbd> key to switch to the next backdrop.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

それぞれの背景でスプライトを切り替えるには、`背景が...になったとき`{:class="block3events"}イベントと一緒に、`表示する`{:class="block3looks"}と</code>隠す`{:class="block3looks"}ブロックを使います。</p>

<p spaces-before="0">The <strong x-id="1">Beachball</strong> sprite:</p>

<pre><code class="blocks3">when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
`</pre>

`緑の旗が押されとき`{:class="block3events"}イベントの`背景を...にする`{:class="block3looks"}で設定した背景で、スプライトの表示が正しく出来てるかを確認しましょう。

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Tip:** You can also make sprites `show`{:class="block3looks"} and `hide`{:class="block3looks"} `when green flag clicked`{:class="block3events"}.
