---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza un'istanza di PreviewSignatureOptions."
type: docs
url: /it/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Inizializza un'istanza di PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sign_options | `SignOptions` | Le opzioni di firma per le quali generare l'anteprima. |
| create_signature_stream | `CreateSignatureStream` | Delegato che crea lo stream di anteprima della firma di output. |

### Esempio

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Buffer di memoria per ricevere l'immagine di anteprima
preview_buffer = io.BytesIO()

def create_stream(options):
    # Restituisci lo stesso buffer per qualsiasi generazione di anteprima
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Genera l'immagine di anteprima nel buffer
Signature.generate_signature_preview(preview_opts)

# Accedi ai byte PNG generati
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Inizializza un oggetto PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sign_options | `SignOptions` | Le opzioni di firma per le quali generare l'anteprima. |
| create_signature_stream | `CreateSignatureStream` | Callable che crea lo stream di anteprima della firma di output. Riceve le opzioni di firma e dovrebbe restituire un `io.RawIOBase` (ad es., `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Callable che rilascia lo stream di anteprima della firma di output. Riceve le opzioni di firma e lo stream e esegue qualsiasi pulizia necessaria. |

### Esempio

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

### Vedi anche
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
