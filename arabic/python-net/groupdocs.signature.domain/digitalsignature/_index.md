---
title: "فئة DigitalSignature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تحتوي الفئة على خصائص التوقيع الرقمي."
type: docs
url: /ar/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

تحتوي الفئة على خصائص التوقيع الرقمي.

نوع DigitalSignature يُظهر الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | يُهيئ توقيعًا رقميًا بالمعلمات الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | يُهيئ توقيعًا رقميًا بمعرف توقيع معروف. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | يُهيئ DigitalSignature باستخدام الشهادة الأولى من مخزن X509 المحدد. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | يُهيئ DigitalSignature بناءً على مخزن X509 المحدد وفهرس الشهادة. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | يُهيئ توقيعًا رقميًا بالشهادة المحددة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | ينسخ نسخة كائن توقيع الباركود. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | يقارن هذا التوقيع بتوقيع آخر للتحقق من المساواة. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | يرجع قيمة التجزئة للتوقيع الرقمي. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | حمّل التواقيع الرقمية من جميع مخازن شهادات X509 النظامية. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | حمّل التواقيع الرقمية من تخزين شهادة. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | حمّل التواقيع الرقمية من تخزين شهادة. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | حمّل التواقيع الرقمية من تخزين شهادة رقمية موجود في موقع محدد. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | يحمّل التواقيع الرقمية من تخزين شهادة رقمية موجود في موقع محدد. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | شهادة X509 المرتبطة بالتوقيع الرقمي. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | اسم المخزن المخصص للشهادة. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | موقع المتجر للشهادة. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | اسم المتجر للشهادة. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | تعليق هدف التوقيع. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | التوقيع الرقمي صالح ولم يتم العبث بالمستند. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | وقت توقيع المستند. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | البصمة الرقمية للشهادة. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | نوع XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
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
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
