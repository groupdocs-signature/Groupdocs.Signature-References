---
title: "الفئة PreviewSignatureOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات معاينة التوقيع."
type: docs
url: /ar/python-net/groupdocs.signature.options/previewsignatureoptions/
is_root: false
weight: 450
---


## PreviewSignatureOptions class

يمثل خيارات معاينة التوقيع.

نوع PreviewSignatureOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream) | يُهيئ مثالًا من PreviewSignatureOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/__init__/#sign_options-create_signature_stream-release_signature_stream) | يُهيئ كائنًا من PreviewSignatureOptions. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/preview_format/) | تنسيق صور المعاينة. |
| [sign_options](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/sign_options/) | خيارات التوقيع لإنشاء معاينة. |
| [signature_id](/signature/python-net/groupdocs.signature.options/previewsignatureoptions/signature_id/) | القيمة الفريدة التي تميز التوقيع. |

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
    print(f"QR code preview: {len(data)} bytes, PNG image: {data.startswith(b'\\x89PNG')}")
```

### Guides
دروس المهام التي تستخدم `PreviewSignatureOptions`:

* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
