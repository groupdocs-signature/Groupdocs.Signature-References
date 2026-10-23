---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يُهيئ مثالًا من PreviewSignatureOptions."
type: docs
url: /ar/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#sign_options-create_signature_stream}

يُهيئ مثالًا من PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| sign_options | `SignOptions` | خيارات التوقيع لإنشاء المعاينة لها. |
| create_signature_stream | `CreateSignatureStream` | المندوب الذي ينشئ تدفق معاينة توقيع الإخراج. |

### مثال

```python
import io
from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

# مخزن الذاكرة لتلقي صورة المعاينة
preview_buffer = io.BytesIO()

def create_stream(options):
    # إرجاع نفس المخزن لأي إنشاء معاينة
    return preview_buffer

qr_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
preview_opts = PreviewSignatureOptions(qr_options, create_stream)

# إنشاء صورة المعاينة داخل المخزن
Signature.generate_signature_preview(preview_opts)

# الوصول إلى بايتات PNG المُولدة
image_data = preview_buffer.getvalue()
print(f"Preview size: {len(image_data)} bytes, PNG: {image_data.startswith(b'\\x89PNG')}")
```

## __init__ {#sign_options-create_signature_stream-release_signature_stream}

يُهيئ كائنًا من PreviewSignatureOptions.

```python
def __init__(self, sign_options, create_signature_stream, release_signature_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| sign_options | `SignOptions` | خيارات التوقيع لإنشاء المعاينة لها. |
| create_signature_stream | `CreateSignatureStream` | قابل للاستدعاء ينشئ تدفق معاينة توقيع الإخراج. يتلقى خيارات التوقيع ويجب أن يُعيد `io.RawIOBase` (مثال: `io.BytesIO`). |
| release_signature_stream | `ReleaseSignatureStream` | قابل للاستدعاء يحرر تدفق معاينة توقيع الإخراج. يتلقى خيارات التوقيع والتدفق ويقوم بأي تنظيف ضروري. |

### مثال

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

### انظر أيضًا
* class [`PreviewSignatureOptions`](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/)
