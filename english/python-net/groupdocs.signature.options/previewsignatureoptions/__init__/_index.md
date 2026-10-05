---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a PreviewSignatureOptions instance."
type: docs
url: /python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Initializes a PreviewSignatureOptions instance.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| sign_options | `SignOptions` | The signature options to generate preview for. |
| create_signature_stream | `CreateSignatureStream` | Delegate that creates the output signature preview stream. |

### Example

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Memory buffer to receive the preview image
preview_buffer = io.BytesIO()

def create_stream(options):
    # Return the same buffer for any preview generation
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Generate the preview image into the buffer
Signature.generate_signature_preview(preview_opts)

# Access the generated PNG bytes
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Initializes a PreviewSignatureOptions object.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| sign_options | `SignOptions` | The signature options to generate preview for. |
| create_signature_stream | `CreateSignatureStream` | Callable that creates the output signature preview stream. It receives the signature options and should return an `io.RawIOBase` (e.g., `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Callable that releases the output signature preview stream. It receives the signature options and the stream and performs any necessary cleanup. |

### Example

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

### See Also
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
