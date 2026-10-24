---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir PreviewSignatureOptions örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

Bir PreviewSignatureOptions örneğini başlatır.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sign_options | `SignOptions` | Önizleme oluşturulacak imza seçenekleri. |
| create_signature_stream | `CreateSignatureStream` | Çıktı imza önizleme akışını oluşturan temsilci. |

### Örnek

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# Önizleme görüntüsünü alacak bellek tamponu
preview_buffer = io.BytesIO()

def create_stream(options):
    # Herhangi bir önizleme oluşturma için aynı tamponu döndür
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# Önizleme görüntüsünü tampon içine oluştur
Signature.generate_signature_preview(preview_opts)

# Oluşturulan PNG baytlarına erişin
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

Bir PreviewSignatureOptions nesnesini başlatır.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sign_options | `SignOptions` | Önizleme oluşturulacak imza seçenekleri. |
| create_signature_stream | `CreateSignatureStream` | Çıktı imza önizleme akışını oluşturan çağrılabilir nesne. İmza seçeneklerini alır ve bir `io.RawIOBase` (ör. `io.BytesIO`) döndürmelidir. |
| release_signature_stream | `ReleaseSignatureStream` | Çıktı imza önizleme akışını serbest bırakan çağrılabilir nesne. İmza seçeneklerini ve akışı alır ve gerekli temizlik işlemlerini gerçekleştirir. |

### Örnek

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

### Ayrıca Bakınız
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
