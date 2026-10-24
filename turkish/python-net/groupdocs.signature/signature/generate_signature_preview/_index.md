---
title: "generate_signature_preview yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Verilen SignOptions temelinde bir imza önizlemesi oluşturur."
type: docs
url: /tr/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

Verilen SignOptions temelinde bir imza önizlemesi oluşturur.

İmzaların önizlemelerini nasıl oluşturacağınız hakkında daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | Verilen SignOptions ile önizleme imzası. |

### Örnek

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Görüntüyü bir dosya yerine tampon belleğe yaz.
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```

### Ayrıca Bakınız
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
