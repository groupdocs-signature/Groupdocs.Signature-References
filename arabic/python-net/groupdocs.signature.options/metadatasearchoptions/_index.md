---
title: "فئة MetadataSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات البيانات الوصفية."
type: docs
url: /ar/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

يمثل خيارات البحث لتوقيعات البيانات الوصفية.

يوفر خيارات لتكوين البحث عن توقيعات البيانات الوصفية في المستند.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

نوع MetadataSearchOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | ينشئ مثيلاً جديدًا من فئة MetadataSearchOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | التنفيذ الخاص بـ [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) المستخدم لفك تشفير جميع توقيعات البيانات الوصفية ضمن مجموعة الخيارات هذه. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | العلم الذي يحدد ما إذا كانت خصائص المستند المدمجة مثل إحصاءات المستند والمعلومات مشمولة في نتيجة البحث. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | اسم توقيع البيانات الوصفية للبحث عنه ومطابقته. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | نوع مطابقة اسم البيانات الوصفية المستخدم في البحث. يُطبق فقط عندما تكون خاصية `name` مُحددة. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
