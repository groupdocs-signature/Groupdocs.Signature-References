---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi sebuah instance PreviewSignatureOptions."
type: docs
url: /id/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Menginisialisasi sebuah instance PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sign_options | `SignOptions` | Opsi tanda tangan untuk menghasilkan pratinjau. |
| create_signature_stream | `CreateSignatureStream` | Delegate yang membuat aliran pratinjau tanda tangan output. |

### Contoh

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Buffer memori untuk menerima gambar pratinjau
preview_buffer = io.BytesIO()

def create_stream(options):
    # Kembalikan buffer yang sama untuk setiap pembuatan pratinjau
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Hasilkan gambar pratinjau ke dalam buffer
Signature.generate_signature_preview(preview_opts)

# Akses byte PNG yang dihasilkan
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Menginisialisasi sebuah objek PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sign_options | `SignOptions` | Opsi tanda tangan untuk menghasilkan pratinjau. |
| create_signature_stream | `CreateSignatureStream` | Callable yang membuat aliran pratinjau tanda tangan output. Ia menerima opsi tanda tangan dan harus mengembalikan sebuah `io.RawIOBase` (misalnya, `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | Callable yang melepaskan aliran pratinjau tanda tangan output. Ia menerima opsi tanda tangan dan aliran tersebut serta melakukan pembersihan yang diperlukan. |

### Contoh

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

### Lihat Juga
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
