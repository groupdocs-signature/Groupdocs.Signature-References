---
title: "فئة BarcodeSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات الباركود."
type: docs
url: /ar/python-net/groupdocs.signature.options/barcodesearchoptions/
is_root: false
weight: 10
---


## BarcodeSearchOptions class

يمثل خيارات البحث لتوقيعات الباركود.

تعرف على المزيد:
- Basic usage of search for Barcode electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Barcode+e-signatures
- Advanced usage of settings of search for Barcode electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Barcode+signatures

يعرض نوع BarcodeSearchOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/) | يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type) | يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بقيمة نوع الترميز. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/#encode_type-text) | يُنشئ مثلاً جديداً من فئة BarcodeSearchOptions بقيم نوع الترميز والنص. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/encode_type/) | نوع الترميز المستخدم لتصفية بحث الباركود؛ إذا لم يُحدد، يشمل البحث جميع أنواع الباركود المدعومة. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/match_type/) | نوع مطابقة نص الباركود المستخدم في البحث. يُستخدم فقط عندما تكون خاصية `text` مُحددة. |
| [return_content](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content/) | العلم الذي يحدد ما إذا كان سيتم استرجاع محتوى صورة الباركود لتوقيع على صفحة المستند. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/return_content_type/) | نوع الملف لمحتوى الصورة المُعاد لتوقيع الباركود عندما تكون خاصية `return_content` مفعلة. |
| [text](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/text/) | نص توقيع الباركود للبحث عنه ومطابقته. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, TextMatchType
from groupdocs.signature.options import BarcodeSearchOptions

with Signature("signed.pdf") as signature:
    options = BarcodeSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.encode_type = BarcodeTypes.CODE128
    options.text = "1234"
    options.match_type = TextMatchType.STARTS_WITH

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching barcode signature(s)")
```

### Guides
أدلة المهام التي تستخدم `BarcodeSearchOptions`:

* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
