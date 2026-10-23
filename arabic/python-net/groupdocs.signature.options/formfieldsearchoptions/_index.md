---
title: "الفئة FormFieldSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات حقول النموذج."
type: docs
url: /ar/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

يمثل خيارات البحث لتوقيعات حقول النموذج.

تعرف على المزيد:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

يعرض نوع FormFieldSearchOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | ينشئ مثيلًا جديدًا من الفئة FormFieldSearchOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | نمط التعبير النمطي المستخدم لمطابقة اسم توقيع حقل النموذج أثناء البحث. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | نوع توقيع حقل النموذج المراد البحث عنه. القيمة الافتراضية هي None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | قيمة توقيع حقل النموذج المراد البحث عنها. القيمة الافتراضية هي None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # إرجاع الحقول النصية فقط التي تحمل الاسم "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
