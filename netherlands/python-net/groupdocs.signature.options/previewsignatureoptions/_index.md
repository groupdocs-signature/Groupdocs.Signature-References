---
title: "PreviewSignatureOptions klasse"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Vertegenwoordigt handtekeningvoorbeeldopties."
type: docs
url: /nl/python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

Vertegenwoordigt handtekeningvoorbeeldopties.

Het PreviewSignatureOptions-type biedt de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | Initialiseert een PreviewSignatureOptions-instantie. |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | Initialiseert een PreviewSignatureOptions-object. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | Het formaat van de voorbeeldafbeeldingen. |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | De handtekeningopties voor het genereren van een voorbeeld. |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | De unieke waarde die de handtekening onderscheidt. |

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
    print(f"QR code preview: {len(data)} bytes, PNG image: {data.startswith(b'\\x89PNG')}")
```

### Guides
Taakgidsen die `PreviewSignatureOptions` gebruiken:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### Zie ook
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
