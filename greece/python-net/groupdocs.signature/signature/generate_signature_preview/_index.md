---
title: "generate_signature_preview μέθοδος"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί προεπισκόπηση υπογραφής βάσει των δεδομένων SignOptions."
type: docs
url: /el/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Δημιουργεί προεπισκόπηση υπογραφής βάσει των δεδομένων SignOptions.

Μάθετε περισσότερα για το πώς να δημιουργήσετε προεπισκοπήσεις των υπογραφών:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | Η προεπισκόπηση υπογραφής με τα δοσμένα SignOptions. |

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
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```

### Δείτε επίσης
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
