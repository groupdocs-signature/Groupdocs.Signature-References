---
title: "color_resolution ιδιότητα"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η ανάλυση χρώματος του GIF."
type: docs
url: /el/python-net/groupdocs.signature.options/gifsaveoptions/color_resolution/
is_root: false
weight: 2020
---


## color_resolution property

Η ανάλυση χρώματος του GIF.

Color Resolution - Αριθμός των δυαδικών ψηφίων ανά πρωτεύον χρώμα που είναι διαθέσιμα στην αρχική εικόνα, μείον 1. Αυτή η τιμή αντιπροσωπεύει το μέγεθος ολόκληρης της παλέτας από την οποία επιλέχθηκαν τα χρώματα του γραφικού, όχι τον αριθμό των χρωμάτων που χρησιμοποιήθηκαν πραγματικά στο γραφικό. Για παράδειγμα, εάν η τιμή σε αυτό το πεδίο είναι 3, τότε η παλέτα της αρχικής εικόνας είχε 4 δυαδικά ψηφία ανά πρωτεύον χρώμα διαθέσιμα για τη δημιουργία της εικόνας. Αυτή η τιμή πρέπει να οριστεί για να υποδείξει τον πλούτο της αρχικής παλέτας, ακόμη και αν δεν είναι διαθέσιμο κάθε χρώμα από ολόκληρη την παλέτα στο μηχάνημα προέλευσης.

### Definition:
```python
@property
def color_resolution(self):
    ...
@color_resolution.setter
def color_resolution(self, value):
    ...
```

### Δείτε επίσης
* class [`GifSaveOptions`](/signature/python-net/groupdocs.signature.options/gifsaveoptions/)
