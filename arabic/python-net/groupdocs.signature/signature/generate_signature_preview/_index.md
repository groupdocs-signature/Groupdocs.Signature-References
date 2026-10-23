---
title: "طريقة generate_signature_preview"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "ينشئ معاينة للتوقيع بناءً على SignOptions المعطاة."
type: docs
url: /ar/python-net/groupdocs.signature/signature/generate_signature_preview/
is_root: false
weight: 1120
---


## generate_signature_preview {#preview_options}

ينشئ معاينة للتوقيع بناءً على SignOptions المعطاة.

تعرف على المزيد حول كيفية إنشاء معاينات للتوقيعات:
- https://docs.groupdocs.com/display/signaturenet/Generate+signatures+preview

```python
def generate_signature_preview(cls, preview_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| preview_options | `PreviewSignatureOptions` | معاينة التوقيع مع SignOptions المحددة. |

### مثال

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # اكتب الصورة في الذاكرة المؤقتة بدلاً من ملف
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

### انظر أيضًا
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
