---
title: PreviewSignatureOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents signature preview options."
type: docs
url: /python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

Represents signature preview options.

The PreviewSignatureOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | Initializes a PreviewSignatureOptions instance. |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | Initializes a PreviewSignatureOptions object. |

### Properties
| Property | Description |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | The preview images format. |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | The signature options for generating a preview. |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | The unique value that distinguishes the signature. |

### Example

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Write the image into the buffer instead of a file
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
Task guides that use `PreviewSignatureOptions`:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
