जब आप एक किताब, एनीमेशन, प्रस्तुति, या स्तरों के साथ खेल बना रहे हैं, तो कुछ स्प्राइट केवल कुछ पृष्ठभूमि पर दिखने चाहिए।
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="" frameborder="0"></iframe>
</div>

`show`{:class="block3looks"} (शो) का उपयोग करें और `hide`{:class="block3looks"} (छिपाएं) ब्लॉकस को `when backdrop switches to`{:class="block3events"} (के साथ जब बैकड्रॉप) ब्लॉक पर बदल जाता है ताकि स्प्राइट केवल वहि बैकड्रॉप पर दिखे जहां वे संबंधित हैं।

**बीचबॉल** स्प्राइट:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

`backdrop`{:class="block3looks"} (बैकड्रॉप) `wheen green flag clicked`{:class="block3events"} (सेट करें जब हरे झंडे) पर क्लिक किया हो ताकि यह सुनिश्चित हो सके कि स्प्राइट्स पहली बैकड्रॉप पर सही तरीके से दिखें या छिपें:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**युक्ति:** `हरे झंडे पर क्लिक करने पर`{:class="block3events"} आप स्प्राइट्स को `शो `{:class="block3looks"}और `हाइड`{:class="block3looks"} भी कर सकते हैं।
