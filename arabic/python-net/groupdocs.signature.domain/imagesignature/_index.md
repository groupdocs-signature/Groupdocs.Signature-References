---
title: "فئة ImageSignature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تحتوي الفئة على خصائص توقيع الصورة."
type: docs
url: /ar/python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 340
---


## ImageSignature class

تحتوي الفئة على خصائص توقيع الصورة.

نوع ImageSignature يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#signature_id) | يُهيئ كائن ImageSignature بمعرّف توقيع فريد يتم الحصول عليه من طريقة Sign أو Search في فئة [`GroupDocs.Signature`](/signature/python-net/groupdocs.signature/signature/). |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/) | استنساخ نسخة ImageSignature. |
| [equals](/signature/python-net/groupdocs.signature.domain/imagesignature/equals/#obj) | يحدد ما إذا كان التوقيع المحدد مساويًا لهذا الكائن. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/imagesignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/imagesignature/get_hash_code/) | يرجع رمز التجزئة للتوقيع. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content/) | بيانات الصورة الثنائية للتوقيع، بالتنسيق المحدد بواسطة [`ImageSignature.Format`](/signature/python-net/groupdocs.signature.domain/imagesignature/format/). |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format/) | تنسيق صورة التوقيع. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size/) | حجم صورة التوقيع بالبايت. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | تاريخ إنشاء التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | ارتفاع التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | العلم الذي يشير إلى ما إذا كان هذا المكوّن يمثل توقيعًا (`True`) أو محتوى مستند (`False`). (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | الموضع الأيسر للتوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | تاريخ تعديل التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | رقم الصفحة التي تم العثور على التوقيع فيها. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | المعرّف الفريد للتوقيع، يُستخدم لتعديل التوقيع في المستند عبر عمليات التحديث أو الحذف. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | نوع التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | الموضع العلوي للتوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | عرض التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([ImageSearchOptions()])
    for image in result.signatures:
        print(
            f"Page {image.page_number}: {image.size} bytes at ({image.left}, {image.top}), "
            f"size {image.width}x{image.height}"
        )
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
