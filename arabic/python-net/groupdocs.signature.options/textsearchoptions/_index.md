---
title: "فئة TextSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات النص."
type: docs
url: /ar/python-net/groupdocs.signature.options/textsearchoptions/
is_root: false
weight: 580
---


## TextSearchOptions class

يمثل خيارات البحث لتوقيعات النص.

تعرف على المزيد:
- Basic usage of search for Text electronic signature by GroupDocs.Signature: [How to eSearch Text signatures in a document](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
- Advanced usage of settings of search for Text electronic signature with GroupDocs.Signature: [Advanced usage of eSearch Text signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

نوع TextSearchOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/) | ينشئ مثيلاً جديداً من فئة TextSearchOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/textsearchoptions/__init__/#text) | ينشئ مثيلاً جديداً من فئة TextSearchOptions بقيمة نصية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/textsearchoptions/match_type/) | نوع مطابقة النص المستخدم في البحث. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textsearchoptions/signature_implementation/) | تنفيذ توقيع النص للبحث. |
| [text](/signature/python-net/groupdocs.signature.options/textsearchoptions/text/) | نص التوقيع للمطابقة عند البحث. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType, TextSignatureImplementation
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    options = TextSearchOptions()
    options.all_pages = False
    options.page_number = 1
    options.text = "John"
    options.match_type = TextMatchType.CONTAINS
    options.signature_implementation = TextSignatureImplementation.NATIVE

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching text signature(s)")
    for ts in result.signatures:
        print(f"'{ts.text}' on page {ts.page_number} at ({ts.left}, {ts.top}), size {ts.width}x{ts.height}")
```

### Guides
دليل المهام الذي يستخدم `TextSearchOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
