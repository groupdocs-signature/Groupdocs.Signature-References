---
title: "StampLine κλάση"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Καθορίστε τις ιδιότητες γραμμής σφραγίδας."
type: docs
url: /el/python-net/groupdocs.signature.domain/stampline/
is_root: false
weight: 680
---


## StampLine class

Καθορίστε τις ιδιότητες γραμμής σφραγίδας.

Ο τύπος StampLine εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/stampline/__init__/) | Αρχικοποιεί ένα StampLine με προεπιλεγμένες τιμές. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [background_color](/signature/python-net/groupdocs.signature.domain/stampline/background_color/) | Το χρώμα φόντου της υπογραφής. |
| [font](/signature/python-net/groupdocs.signature.domain/stampline/font/) | Η γραμματοσειρά του κειμένου της γραμμής σφραγίδας. |
| [height](/signature/python-net/groupdocs.signature.domain/stampline/height/) | Το ύψος γραμμής στη σφραγίδα. |
| [inner_border](/signature/python-net/groupdocs.signature.domain/stampline/inner_border/) | Το εσωτερικό περίγραμμα της γραμμής σφραγίδας. |
| [outer_border](/signature/python-net/groupdocs.signature.domain/stampline/outer_border/) | Το εξωτερικό περιθώριο της γραμμής σφραγίδας. |
| [text](/signature/python-net/groupdocs.signature.domain/stampline/text/) | Το κείμενο της γραμμής σφραγίδας. |
| [text_bottom_intent](/signature/python-net/groupdocs.signature.domain/stampline/text_bottom_intent/) | Η κάτω πρόθεση του κειμένου. |
| [text_color](/signature/python-net/groupdocs.signature.domain/stampline/text_color/) | Το χρώμα κειμένου της υπογραφής. |
| [text_repeat_type](/signature/python-net/groupdocs.signature.domain/stampline/text_repeat_type/) | Ο τύπος επανάληψης κειμένου. |
| [visible](/signature/python-net/groupdocs.signature.domain/stampline/visible/) | Η ορατότητα της γραμμής σφραγίδας. |

### Παράδειγμα

```python
from groupdocs.signature.domain import StampLine
from groupdocs.pydrawing import Color

# Δημιουργία γραμμής σφραγίδας
line = StampLine()
line.text = " * European Union *"
line.font.size = 12
line.height = 22
line.text_bottom_intent = 6
line.text_color = Color.white_smoke
line.background_color = Color.dark_slate_blue
```

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
