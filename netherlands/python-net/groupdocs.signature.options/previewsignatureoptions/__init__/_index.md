---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een PreviewSignatureOptions-instantie."
type: docs
url: /nl/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Initialiseert een PreviewSignatureOptions-instantie.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sign_options | `SignOptions` | De handtekeningopties waarvoor een preview moet worden gegenereerd. |
| create_signature_stream | `CreateSignatureStream` | Delegate die de uitvoerhandtekeningpreviewstream maakt. |

### Voorbeeld

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Geheugenbuffer om de previewafbeelding te ontvangen.
preview_buffer = io.BytesIO()

def create_stream(options):
    # Retourneer dezelfde buffer voor elke previewgeneratie.
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Genereer de previewafbeelding in de buffer.
Signature.generate_signature_preview(preview_opts)

# Toegang tot de gegenereerde PNG-bytes.
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Initialiseert een PreviewSignatureOptions-object.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sign_options | `SignOptions` | De handtekeningopties waarvoor een preview moet worden gegenereerd. |
| create_signature_stream | `CreateSignatureStream` | Callable die de uitvoerhandtekeningpreviewstream maakt. Het ontvangt de handtekeningopties en moet een `io.RawIOBase` retourneren (bijv. `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Callable die de uitvoerhandtekeningpreviewstream vrijgeeft. Het ontvangt de handtekeningopties en de stream en voert eventuele noodzakelijke opruimacties uit. |

### Voorbeeld

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

### Zie ook
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
