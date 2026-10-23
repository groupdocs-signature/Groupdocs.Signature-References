---
title: "PreviewSignatureOptions‑Klasse"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Stellt Signaturvorschau-Optionen dar."
type: docs
url: /de/python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

Stellt Signaturvorschau-Optionen dar.

Der Typ PreviewSignatureOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | Initialisiert eine PreviewSignatureOptions‑Instanz. |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | Initialisiert ein PreviewSignatureOptions‑Objekt. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | Das Format der Vorschaubilder. |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | Die Signaturoptionen zum Erzeugen einer Vorschau. |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | Der eindeutige Wert, der die Signatur unterscheidet. |

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
    print(f"QR code preview: {len(data)} bytes, PNG image: {data.startswith(b'\\x89PNG')}")
```

### Guides
Aufgaben‑Leitfäden, die `PreviewSignatureOptions` verwenden:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Siehe auch
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
