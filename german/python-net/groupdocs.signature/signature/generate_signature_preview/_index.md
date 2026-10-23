---
title: "generate_signature_preview Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Erstellt eine Signaturvorschau basierend auf den angegebenen SignOptions."
type: docs
url: /de/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Erstellt eine Signaturvorschau basierend auf den angegebenen SignOptions.

Erfahren Sie mehr darüber, wie Vorschauen der Signaturen erzeugt werden:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | Die Vorschausignatur mit den angegebenen SignOptions. |

### Beispiel

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Schreibe das Bild in den Puffer anstelle einer Datei
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

### Siehe auch
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
