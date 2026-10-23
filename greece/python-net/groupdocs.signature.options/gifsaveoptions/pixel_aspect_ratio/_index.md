---
title: "pixel_aspect_ratio ιδιότητα"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η αναλογία διαστάσεων pixel του GIF."
type: docs
url: /el/python-net/groupdocs.signature.options/gifsaveoptions/pixel_aspect_ratio/
is_root: false
weight: 2070
---


## pixel_aspect_ratio property

Η αναλογία διαστάσεων pixel του GIF.

Pixel Aspect Ratio – παράγοντας που χρησιμοποιείται για τον υπολογισμό μιας προσέγγισης της αναλογίας διαστάσεων του pixel στην αρχική εικόνα. Εάν η τιμή του πεδίου δεν είναι 0, αυτή η προσέγγιση της αναλογίας διαστάσεων υπολογίζεται βάσει του τύπου:

Aspect Ratio = (Pixel Aspect Ratio + 15) / 64

Το Pixel Aspect Ratio ορίζεται ως το πηλίκο του πλάτους του pixel προς το ύψος του. Η τιμή σε αυτό το πεδίο επιτρέπει τον καθορισμό του πιο πλατιάς pixel 4:1 έως του πιο ψηλού pixel 1:4 με βήματα 1/64.

Τιμές:
- 0 – No aspect ratio information is given.
- 1..255 – Value used in the computation.

### Definition:
```python
@property
def pixel_aspect_ratio(self):
    ...
@pixel_aspect_ratio.setter
def pixel_aspect_ratio(self, value):
    ...
```

### Δείτε επίσης
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
