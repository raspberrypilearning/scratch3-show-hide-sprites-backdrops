Όταν δημιουργείς ένα βιβλίο, ένα κινούμενο σχέδιο, μια παρουσίαση ή ένα παιχνίδι με επίπεδα, ορισμένα αντικείμενα θα πρέπει να εμφανίζονται μόνο σε ορισμένα υπόβαθρα.

**Εμφάνιση και απόκρυψη αντικειμένων σε διαφορετικά υπόβαθρα**: [Δες μέσα](https://scratch.mit.edu/projects/499876704/editor){:target="_blank"}
Κάνε κλικ στη Σκηνή ή πάτα το πλήκτρο <kbd>Διάστημα</kbd> για να μεταβείς στο επόμενο υπόβαθρο.
<div class="scratch-preview" style="margin-left: 15px;">
  <iframe allowtransparency="true" width="485" height="402" src="https://scratch.mit.edu/projects/embed/499876704/?autostart=false" frameborder="0"></iframe>
</div>

Χρησιμοποίησε τα `εμφανίσου`{:class="block3looks"} και `εξαφανίσου`{:class="block3looks"} με το `όταν το υπόβαθρο αλλάξει σε`{:class="block3events"} για να κάνεις τα αντικείμενα να εμφανίζονται μόνο στα υπόβαθρα στα οποία ανήκουν.

Το αντικείμενο**Beachball**:
```blocks3
when backdrop switches to [Beach Rio v]
show

when backdrop switches to [Soccer 2 v]
hide
```

Όρισε το `υπόβαθρο`{:class="block3looks"} `όταν γίνει κλικ στην πράσινη σημαία`{:class="block3events"} για να βεβαιωθείς ότι τα αντικείμενα εμφανίζονται ή κρύβονται σωστά στο πρώτο υπόβαθρο:

```blocks3
when flag clicked
switch backdrop to [Beach Rio v]
```

**Υπόδειξη:** Μπορείς επίσης να χρησιμοποιήσεις τα μπλοκ `εμφανίσου`{:class="block3looks"} και `εξαφανίσου`{:class="block3looks"} για τα αντικείμενα`όταν γίνει κλικ στην πράσινη σημαία`{:class="block3events"}.
