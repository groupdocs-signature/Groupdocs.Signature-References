---
title: "κλάση PreviewSignatureOptions"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει τις επιλογές προεπισκόπησης υπογραφής."
type: docs
url: /el/python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

Αντιπροσωπεύει τις επιλογές προεπισκόπησης υπογραφής.

Ο τύπος PreviewSignatureOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | Αρχικοποιεί μια παρουσία PreviewSignatureOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | Αρχικοποιεί ένα αντικείμενο PreviewSignatureOptions. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | Η μορφή των εικόνων προεπισκόπησης. |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | Οι επιλογές υπογραφής για τη δημιουργία προεπισκόπησης. |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | Η μοναδική τιμή που διακρίνει την υπογραφή. |

### Παράδειγμα

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Γράψτε την εικόνα στο buffer αντί για αρχείο
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    print(f"QR code preview: {len(data)} bytes, PNG image: {data.startswith(b'\\x89PNG')}")
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `PreviewSignatureOptions`:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Δείτε επίσης
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
