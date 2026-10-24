---
title: "metodo generate_signature_preview"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Genera un'anteprima della firma basata sulle SignOptions fornite."
type: docs
url: /it/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Genera un'anteprima della firma basata sulle SignOptions fornite.

Scopri di più su come generare anteprime delle firme:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | L'anteprima della firma con i SignOptions forniti. |

### Esempio

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Scrivi l'immagine nel buffer invece che in un file
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

### Vedi anche
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
