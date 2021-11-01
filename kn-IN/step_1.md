ನೀವು ಪುಸ್ತಕ, ಅನಿಮೇಶನ್, ಪ್ರಸ್ತುತಿ ಅಥವಾ ಆಟವನ್ನು ಮಟ್ಟಗಳೊಂದಿಗೆ ರಚಿಸುವಾಗ, ಕೆಲವು ಸ್ಪ್ರೈಟ್‌ಗಳು ಕೆಲವು ಬ್ಯಾಕ್‌ಡ್ರಾಪ್‌ಗಳಲ್ಲಿ ಮಾತ್ರ ತೋರಿಸಬೇಕು.

**ವಿವಿಧ ಹಿನ್ನೆಲೆ ಮೇಲೆ ತೋರಿಸಿ ಹಾಗೂ ಮರೆಮಾಡಿ ಅತಿಮಾನುಷ**: [ಒಳಗಡೆ ವೀಕ್ಷಿಸಿ](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
ಪತ್ರಿಕಾ ಸ್ಟೇಜ್ ಮೇಲೆ ಕ್ಲಿಕ್ ಅಥವಾ <kbd>ಸ್ಪೇಸ್</kbd> ಸ್ವಿಚ್ ಕೀಲಿಯನ್ನು ಮುಂದಿನ ಬ್ಯಾಕ್ಟ್ರಾಪ್ಗೆ.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

ಅವುಗಳಿಗೆ ಸೇರಿದ ಸ್ಪ್ರೈಟ್ ಅನ್ನು ಮಾತ್ರ ಬ್ಯಾಕ್ಡ್ರಾಪ್ ಮೇಲೆ ತೋರಿಸಲು `when backdrop switches to`{:class="block3events"} ಬ್ಲಾಕ್ ಜೊತೆಗೆ `show`{:class="block3looks"} ಮತ್ತು `hide`{:class="block3looks"} ಬ್ಲಾಕ್ ಅನ್ನು ಬಳಸಿ.

**Beachball** ಸ್ಪ್ರೈಟ್:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

ಮೊದಲ ಬ್ಯಾಕ್ಡ್ರಾ ಮೇಲೆ ಸ್ಪ್ರೈಟ್ ಗಳು ಕಾಣುತ್ತವೆ ಅಥವಾ ಮರೆಮಾಡುತ್ತವೆ ಎಂಬುವುದನ್ನು ಖಚಿತಪಡಿಸಿಕೊಳ್ಳಲು `backdrop`{:class="block3looks"} `when green flag clicked`{:class="block3events"} ಅನ್ನು ಸೆಟ್ ಮಾಡಿ:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**ಸಲಹೆ:**when green flag clicked</code>{: class = "block3events"} ಅನ್ನು ಕ್ಲಿಕ್ ಮಾಡಿದಾಗ ನೀವು `show`{: class = "block3looks}} ಮತ್ತು `hide`{: class =" block3looks "} .</p>
