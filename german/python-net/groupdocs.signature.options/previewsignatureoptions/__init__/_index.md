---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine PreviewSignatureOptions‑Instanz."
type: docs
url: /de/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Initialisiert eine PreviewSignatureOptions‑Instanz.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sign_options | `SignOptions` | Die Signaturoptionen, für die eine Vorschau generiert werden soll. |
| create_signature_stream | `CreateSignatureStream` | Delegat, der den Ausgabesignatur-Vorschau-Stream erstellt. |

### Beispiel

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Speicherpuffer zum Empfangen des Vorschaubildes
preview_buffer = io.BytesIO()

def create_stream(options):
    # Gibt denselben Puffer für jede Vorschauerstellung zurück
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Generiere das Vorschaubild in den Puffer
Signature.generate_signature_preview(preview_opts)

# Greife auf die erzeugten PNG‑Bytes zu
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Initialisiert ein PreviewSignatureOptions‑Objekt.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sign_options | `SignOptions` | Die Signaturoptionen, für die eine Vorschau generiert werden soll. |
| create_signature_stream | `CreateSignatureStream` | Aufrufbare, die den Ausgabesignatur‑Vorschau‑Stream erstellt. Sie erhält die Signaturoptionen und sollte ein `io.RawIOBase` (z. B. `io.BytesIO`) zurückgeben. |
| release_signature_stream | `ReleaseSignatureStream` | Aufrufbare, die den Ausgabesignatur‑Vorschau‑Stream freigibt. Sie erhält die Signaturoptionen und den Stream und führt die erforderliche Bereinigung durch. |

### Beispiel

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

### Siehe auch
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
