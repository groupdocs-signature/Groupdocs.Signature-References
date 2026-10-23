---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une instance de PreviewSignatureOptions."
type: docs
url: /fr/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Initialise une instance de PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| sign_options | `SignOptions` | Les options de signature pour lesquelles générer l'aperçu. |
| create_signature_stream | `CreateSignatureStream` | Délégué qui crée le flux d'aperçu de signature de sortie. |

### Exemple

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Tampon mémoire pour recevoir l'image d'aperçu
preview_buffer = io.BytesIO()

def create_stream(options):
    # Retourner le même tampon pour toute génération d'aperçu
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Générer l'image d'aperçu dans le tampon
Signature.generate_signature_preview(preview_opts)

# Accéder aux octets PNG générés
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Initialise un objet PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| sign_options | `SignOptions` | Les options de signature pour lesquelles générer l'aperçu. |
| create_signature_stream | `CreateSignatureStream` | Objet appelable qui crée le flux d'aperçu de signature de sortie. Il reçoit les options de signature et doit retourner un `io.RawIOBase` (par ex., `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Objet appelable qui libère le flux d'aperçu de signature de sortie. Il reçoit les options de signature et le flux et effectue le nettoyage nécessaire. |

### Exemple

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

### Voir aussi
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
