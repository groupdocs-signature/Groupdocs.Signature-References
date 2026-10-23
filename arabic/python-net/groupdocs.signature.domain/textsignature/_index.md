---
title: "فئة TextSignature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تحتوي فئة TextSignature على خصائص التوقيع النصي."
type: docs
url: /ar/python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 770
---


## TextSignature class

تحتوي فئة TextSignature على خصائص التوقيع النصي.

يعرض نوع TextSignature الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#signature_id) | يُهيئ كائن TextSignature بمعرف التوقيع الفريد المستخرج من عملية توقيع أو بحث. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/) | ينسخ نسخة من كائن Text Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textsignature/equals/#obj) | يقارن التوقيع المحدد مع هذه النسخة للتحقق من المساواة. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textsignature/get_hash_code/) | يرجع رمز التجزئة للتوقيع. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native/) | السمة الأصلية التي تشير إلى ما إذا كان التوقيع خاصًا بالمستند. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation/) | تنفيذ توقيع النص. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text/) | نص التوقيع. |
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
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for text_sig in result.signatures:
        print(f"Text: {text_sig.text}, Position: ({text_sig.left}, {text_sig.top}), Size: {text_sig.width}x{text_sig.height}")
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
