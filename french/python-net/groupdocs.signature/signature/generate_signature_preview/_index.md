---
title: "méthode generate_signature_preview"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Génère un aperçu de signature basé sur les SignOptions fournis."
type: docs
url: /fr/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Génère un aperçu de signature basé sur les SignOptions fournis.

En savoir plus sur la façon de générer des aperçus des signatures:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | La signature d'aperçu avec les SignOptions données. |

### Exemple

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Écrire l'image dans le tampon au lieu d'un fichier
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

### Voir aussi
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
