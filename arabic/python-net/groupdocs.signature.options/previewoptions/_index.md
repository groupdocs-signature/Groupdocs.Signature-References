---
title: "فئة PreviewOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات معاينة المستند."
type: docs
url: /ar/python-net/groupdocs.signature.options/previewoptions/
is_root: false
weight: 430
---


## PreviewOptions class

يمثل خيارات معاينة المستند.

نوع PreviewOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-resolution-page_numbers) |  |
| [__init__](/signature/python-net/groupdocs.signature.options/previewoptions/__init__/#create_page_stream-release_page_stream-resolution-page_numbers) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [height](/signature/python-net/groupdocs.signature.options/previewoptions/height/) | ارتفاع صور المعاينة. |
| [hide_signatures](/signature/python-net/groupdocs.signature.options/previewoptions/hide_signatures/) | العلم الذي يشير إلى ما إذا كانت التوقيعات مخفية عن صور معاينة الصفحة. |
| [page_numbers](/signature/python-net/groupdocs.signature.options/previewoptions/page_numbers/) | أرقام صفحات صور المعاينة. |
| [preview_format](/signature/python-net/groupdocs.signature.options/previewoptions/preview_format/) | تنسيق صور المعاينة. |
| [resolution](/signature/python-net/groupdocs.signature.options/previewoptions/resolution/) | دقة صور المعاينة بوحدة DPI (نقطة لكل بوصة). الدقة الافتراضية هي 96 DPI. |
| [width](/signature/python-net/groupdocs.signature.options/previewoptions/width/) | عرض صورة المعاينة. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import PreviewOptions

def create_page_stream(page_data):
    image_name = f"preview_page_{page_data.page_number}.png"
    print(f"Saving page {page_data.page_number + 1} to {image_name}")
    return open(image_name, "wb")

with Signature("sample.pdf") as signature:
    preview_options = PreviewOptions(create_page_stream)
    preview_options.preview_format = PreviewOptions.PreviewFormats.PNG
    signature.generate_preview(preview_options)
```

### Guides
دليل المهام الذي يستخدم `PreviewOptions`:

* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
