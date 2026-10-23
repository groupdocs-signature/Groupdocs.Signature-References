---
title: "Κλάση SignatureFont"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Η κλάση SignatureFont καθορίζει τις ιδιότητες γραμματοσειράς για μια υπογραφή κειμένου."
type: docs
url: /el/python-net/groupdocs.signature.domain/signaturefont/
is_root: false
weight: 620
---


## SignatureFont class

Η κλάση SignatureFont καθορίζει τις ιδιότητες γραμματοσειράς για μια υπογραφή κειμένου.

Ο τύπος SignatureFont εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/signaturefont/__init__/) | Αρχικοποιεί ένα SignatureFont με προεπιλεγμένες τιμές. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [bold](/signature/python-net/groupdocs.signature.domain/signaturefont/bold/) | Το έντονο στυλ της γραμματοσειράς. |
| [family_name](/signature/python-net/groupdocs.signature.domain/signaturefont/family_name/) | Το όνομα οικογένειας γραμματοσειράς. |
| [italic](/signature/python-net/groupdocs.signature.domain/signaturefont/italic/) | Το πλάγιο στυλ της γραμματοσειράς. |
| [size](/signature/python-net/groupdocs.signature.domain/signaturefont/size/) | Το μέγεθος γραμματοσειράς. |
| [strikeout](/signature/python-net/groupdocs.signature.domain/signaturefont/strikeout/) | Το στυλ διαγράμμισης της γραμματοσειράς. |
| [underline](/signature/python-net/groupdocs.signature.domain/signaturefont/underline/) | Το στυλ υπογράμμισης της γραμματοσειράς. |

### Παράδειγμα

```python
from groupdocs.signature.domain import SignatureFont

font = SignatureFont()
font.family_name = "Arial"
font.size = 20
font.bold = True
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `SignatureFont`:

* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Δείτε επίσης
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
