ನೀವು ಪುಸ್ತಕ, ಅನಿಮೇಶನ್, ಪ್ರಸ್ತುತಿ ಅಥವಾ ಆಟವನ್ನು ಮಟ್ಟಗಳೊಂದಿಗೆ ರಚಿಸುವಾಗ, ಕೆಲವು ಸ್ಪ್ರೈಟ್‌ಗಳು ಕೆಲವು ಬ್ಯಾಕ್‌ಡ್ರಾಪ್‌ಗಳಲ್ಲಿ ಮಾತ್ರ ತೋರಿಸಬೇಕು.

**Show and hide sprites on different backdrops**: [See inside](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Click on the Stage or press the <kbd>Space</kbd> key to switch to the next backdrop.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
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
