---
title: "generate_signature_preview methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Genereert een handtekeningvoorbeeld op basis van de opgegeven SignOptions."
type: docs
url: /nl/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Genereert een handtekeningvoorbeeld op basis van de opgegeven SignOptions.

Leer meer over hoe je previews van de handtekeningen kunt genereren:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | De previewhandtekening met gegeven SignOptions. |

### Voorbeeld

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Schrijf de afbeelding naar de buffer in plaats van naar een bestand
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

### Zie ook
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
