---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en PreviewSignatureOptions-instans."
type: docs
url: /sv/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Initierar en PreviewSignatureOptions-instans.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sign_options | `SignOptions` | Signaturalternativen för att generera förhandsgranskning för. |
| create_signature_stream | `CreateSignatureStream` | Delegat som skapar förhandsgranskningsströmmen för utdata‑signaturen. |

### Exempel

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Minnesbuffert för att ta emot förhandsgranskningsbilden
preview_buffer = io.BytesIO()

def create_stream(options):
    # Returnera samma buffert för alla förhandsgranskningsgenereringar
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Generera förhandsgranskningsbilden i bufferten
Signature.generate_signature_preview(preview_opts)

# Åtkomst till de genererade PNG-byterna
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Initierar ett PreviewSignatureOptions-objekt.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sign_options | `SignOptions` | Signaturalternativen för att generera förhandsgranskning för. |
| create_signature_stream | `CreateSignatureStream` | Anropbar som skapar förhandsgranskningsströmmen för utdata‑signaturen. Den tar emot signaturalternativen och bör returnera ett `io.RawIOBase` (t.ex. `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Anropbar som frigör förhandsgranskningsströmmen för utdata‑signaturen. Den tar emot signaturalternativen och strömmen och utför eventuell nödvändig städning. |

### Exempel

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

### Se även
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
