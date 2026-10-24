---
title: "método generate_signature_preview"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Genera una vista previa de la firma basada en los SignOptions proporcionados."
type: docs
url: /es/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Genera una vista previa de la firma basada en los SignOptions proporcionados.

Aprende más sobre cómo generar vistas previas de las firmas:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | La firma de vista previa con los SignOptions dados. |

### Ejemplo

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Escribe la imagen en el búfer en lugar de un archivo
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

### Ver también
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
