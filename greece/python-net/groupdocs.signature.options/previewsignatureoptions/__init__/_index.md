---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία PreviewSignatureOptions."
type: docs
url: /el/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Αρχικοποιεί μια παρουσία PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sign_options | `SignOptions` | Οι επιλογές υπογραφής για τις οποίες θα δημιουργηθεί προεπισκόπηση. |
| create_signature_stream | `CreateSignatureStream` | Αντιπρόσωπος που δημιουργεί τη ροή προεπισκόπησης της εξόδου υπογραφής. |

### Παράδειγμα

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Προσωρινή μνήμη για λήψη της εικόνας προεπισκόπησης.
preview_buffer = io.BytesIO()

def create_stream(options):
    # Επιστρέψτε την ίδια προσωρινή μνήμη για οποιαδήποτε δημιουργία προεπισκόπησης.
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Δημιουργήστε την εικόνα προεπισκόπησης στη προσωρινή μνήμη.
Signature.generate_signature_preview(preview_opts)

# Πρόσβαση στα παραγόμενα bytes PNG.
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Αρχικοποιεί ένα αντικείμενο PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sign_options | `SignOptions` | Οι επιλογές υπογραφής για τις οποίες θα δημιουργηθεί προεπισκόπηση. |
| create_signature_stream | `CreateSignatureStream` | Κλήσιμο που δημιουργεί τη ροή προεπισκόπησης της εξόδου υπογραφής. Λαμβάνει τις επιλογές υπογραφής και πρέπει να επιστρέφει ένα `io.RawIOBase` (π.χ., `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Κλήσιμο που απελευθερώνει τη ροή προεπισκόπησης της εξόδου υπογραφής. Λαμβάνει τις επιλογές υπογραφής και τη ροή και εκτελεί τυχόν απαραίτητη εκκαθάριση. |

### Παράδειγμα

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_qr_code_image():
    result = io.BytesIO()
    qr_options = QrCodeSignOptions()
    qr_options.encode_type = QrCodeTypes.QR
    qr_options.text = "Case 148-01"

    preview_options = PreviewSignatureOptions(
        qr_options,
        lambda options: result,
        lambda options, stream: None,
    )
    Signature.generate_signature_preview(preview_options)

    with open("qr_code_result.png", "wb") as f:
        f.write(result.getvalue())
```

### Δείτε επίσης
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
