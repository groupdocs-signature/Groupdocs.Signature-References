---
title: "فئة TextFormFieldSignature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خصائص توقيع حقل نموذج إدخال نصي لمستندات PDF."
type: docs
url: /ar/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

يمثل خصائص توقيع حقل نموذج إدخال نصي لمستندات PDF.

يعرض نوع TextFormFieldSignature الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | يُهيئ PdfTextFormFieldSignature باسم محدد مسبقًا. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | يُهيئ PdfTextFormFieldSignature باسم محدد مسبقًا. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | استنساخ نسخة من FormField Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | يقارن هذا التوقيع بتوقيع آخر للتحقق من المساواة بناءً على النوع وقيم الخصائص. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | يتجاوز طريقة GetHashCode. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | نص إدخال حقل النموذج. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | تاريخ إنشاء التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | ارتفاع التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | العلم الذي يشير إلى ما إذا كان هذا المكوّن يمثل توقيعًا (`True`) أو محتوى مستند (`False`). (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | الموضع الأيسر للتوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | تاريخ تعديل التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | اسم حقل النموذج الفريد. (موروث من [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | رقم الصفحة التي تم العثور على التوقيع فيها. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | المعرّف الفريد للتوقيع، يُستخدم لتعديل التوقيع في المستند عبر عمليات التحديث أو الحذف. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | نوع التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | الموضع العلوي للتوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | نوع حقل النموذج. (موروث من [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | كائن بيانات حقل النموذج. (موروث من [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | عرض التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # إنشاء حقل نموذج نصي باسم "FieldText" بالقيمة "Value1"
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # إنشاء خيارات حقل النموذج له
        options = FormFieldSignOptions(text_field)

        # تعيين موضع وحجم حقل النموذج
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # توقيع المستند وحفظ النتيجة
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
