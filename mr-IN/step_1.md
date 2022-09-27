जेव्हा तुम्ही पुस्तक, अॅनिमेशन, प्रेझेंटेशन किंवा लेव्हल्ससह गेम तयार करत असाल, तेव्हा काही स्प्राइट्स फक्त काही पार्श्वभूमीवर दिसले पाहिजेत.

**वेगवेगळ्या पार्श्वभूमीवर स्प्राइट्स दाखवा आणि लपवा**: [आत पहा](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
पुढील पार्श्वभूमीवर जाण्यासाठी स्टेज वर क्लिक करा किंवा <kbd>स्पेस</kbd> बटण दाबा.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

स्प्राईट्स जिथे असायला पाहिजे फक्त त्याच पार्श्वभूमीवर दाखवण्यासाठी `show`{:class="block3looks"} आणि `hide`{:class="block3looks"} हे ब्लॉक्स `when backdrop switches to`{:class="block3events"} या ब्लॉक सोबत वापरा.

**बीचबॉल** स्प्राइट:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

पहिल्या पार्श्वभूमीवर स्प्राइट्स योग्यरित्या दाखविले किंवा लपविले जात आहेत याची खात्री करण्यासाठी `backdrop`{:class="block3looks"} `when green flag clicked` निश्चित करा:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**टीप:** तुम्ही स्प्राईट्स `show`{:class="block3looks"} आणि `hide`{:class="block3looks"} करू शकता `when green flag clicked`{:class="block3events"}.
