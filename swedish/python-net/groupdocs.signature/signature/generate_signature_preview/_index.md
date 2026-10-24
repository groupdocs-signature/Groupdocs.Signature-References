---
title: "generate_signature_preview metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Genererar en signaturförhandsgranskning baserad på de givna SignOptions."
type: docs
url: /sv/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Genererar en signaturförhandsgranskning baserad på de givna SignOptions.

Läs mer om hur du genererar förhandsgranskningar av signaturerna:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | Förhandsgranskningssignaturen med angivna SignOptions. |

### Exempel

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Skriv bilden till bufferten istället för en fil
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

### Se även
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
