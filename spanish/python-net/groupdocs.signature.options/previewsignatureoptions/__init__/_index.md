---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una instancia de PreviewSignatureOptions."
type: docs
url: /es/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Inicializa una instancia de PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sign_options | `SignOptions` | Las opciones de firma para generar la vista previa. |
| create_signature_stream | `CreateSignatureStream` | Delegado que crea el flujo de vista previa de la firma de salida. |

### Ejemplo

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Buffer de memoria para recibir la imagen de vista previa
preview_buffer = io.BytesIO()

def create_stream(options):
    # Devuelve el mismo buffer para cualquier generación de vista previa
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Genera la imagen de vista previa en el buffer
Signature.generate_signature_preview(preview_opts)

# Accede a los bytes PNG generados
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Inicializa un objeto PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sign_options | `SignOptions` | Las opciones de firma para generar la vista previa. |
| create_signature_stream | `CreateSignatureStream` | Callable que crea el flujo de vista previa de la firma de salida. Recibe las opciones de firma y debe devolver un `io.RawIOBase` (p. ej., `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Callable que libera el flujo de vista previa de la firma de salida. Recibe las opciones de firma y el flujo y realiza cualquier limpieza necesaria. |

### Ejemplo

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

### Ver también
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
