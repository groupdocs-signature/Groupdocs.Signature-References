---
title: "الفئة ImageSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات الصورة."
type: docs
url: /ar/python-net/groupdocs.signature.options/imagesearchoptions/
is_root: false
weight: 240
---


## ImageSearchOptions class

يمثل خيارات البحث لتوقيعات الصورة.

تعرف على المزيد:
- Basic usage of search for Image electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Image+e-signatures
- Advanced usage of settings of search for Image electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Image+signatures

نوع ImageSearchOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesearchoptions/__init__/) | يُنشئ نسخة جديدة من الفئة ImageSearchOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [max_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/max_content_size/) | الحد الأقصى لحجم الصور لمعيار البحث، بالبايت. |
| [min_content_size](/signature/python-net/groupdocs.signature.options/imagesearchoptions/min_content_size/) | الحد الأدنى لحجم بيانات الصورة، بالبايت، الذي يُؤخذ في الاعتبار أثناء البحث. قيمة غير صفرية تحدد الحد الأدنى؛ القيمة الافتراضية هي صفر، والتي لا تؤثر على نتيجة البحث. |
| [return_content](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content/) | العلم الذي يحدد ما إذا كان محتوى صورة التوقيع يُعاد. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/imagesearchoptions/return_content_type/) | نوع الملف لمحتوى الصورة المعاد عندما تكون الخاصية `return_content` مفعلة. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

def extract_image_signatures():
    with Signature("signed.pdf") as signature:
        options = ImageSearchOptions()
        options.all_pages = False          # search the first page only
        options.page_number = 1
        options.min_content_size = 1024   # skip images smaller than 1 KB
        options.return_content = True
        options.return_content_type = FileType.PNG

        result = signature.search([options])
        for i, image in enumerate(result.signatures, start=1):
            file_name = f"image_signature_{i}.png"
            with open(file_name, "wb") as out:
                out.write(image.content)
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
