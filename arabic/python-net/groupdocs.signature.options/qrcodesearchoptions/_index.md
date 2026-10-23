---
title: "فئة QrCodeSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات QR-Code."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

يمثل خيارات البحث لتوقيعات QR-Code.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

نوع QrCodeSearchOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | ينشئ مثيلًا جديدًا من فئة QRCodeSearchOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | ينشئ مثيلًا جديدًا من فئة QRCodeSearchOptions بقيمة نوع الترميز. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | يُنشئ مثيلاً جديدًا من الفئة QRCodeSearchOptions مع نوع الترميز وقيم النص. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | تنفيذ [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) يُستخدم لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | نوع الترميز للبحث عن رموز QR. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | نوع مطابقة نص QR-Code المستخدم أثناء البحث. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | العلم الذي يحدد ما إذا كان محتوى صورة QR‑Code يُعاد لكل توقيع في صفحة المستند. عندما يُضبط على True، تُحفظ بيانات الصورة الخام في خاصية التوقيع `content` باستخدام الصيغة المحددة بـ `return_content_type`. يكون معطلاً بشكل افتراضي. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | نوع الملف لمحتوى الصورة المعاد لتوقيع QR-Code عندما تكون خاصية `return_content` مفعلة. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | نص توقيع QR-Code للبحث والمطابقة. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
