---
title: "Κλάση Border"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά την εμφάνιση του περιγράμματος."
type: docs
url: /el/python-net/groupdocs.signature.domain/border/
is_root: false
weight: 60
---


## Border class

Αναπαριστά την εμφάνιση του περιγράμματος.

Ο τύπος Border εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/border/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/border/clone/) | Υλοποιεί τη διεπαφή IClonable. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [color](/signature/python-net/groupdocs.signature.domain/border/color/) | Το χρώμα περιγράμματος της υπογραφής. |
| [dash_style](/signature/python-net/groupdocs.signature.domain/border/dash_style/) | Το στυλ περιγράμματος της υπογραφής. |
| [transparency](/signature/python-net/groupdocs.signature.domain/border/transparency/) | Η διαφάνεια περιγράμματος της υπογραφής, κυμαίνεται από 0.0 (αδιαφανές) έως 1.0 (διαυγές), προεπιλογή 0 (αδιαφανές). |
| [visible](/signature/python-net/groupdocs.signature.domain/border/visible/) | Η ορατότητα του περιγράμματος. |
| [weight](/signature/python-net/groupdocs.signature.domain/border/weight/) | Το βάρος του περιγράμματος της υπογραφής. |

### Παράδειγμα

```python
from groupdocs.signature.domain import Border, DashStyle
from groupdocs.pydrawing import Color

border = Border()
border.color = Color.dark_green
border.dash_style = DashStyle.DASH
border.weight = 2
border.visible = True
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `Border`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
