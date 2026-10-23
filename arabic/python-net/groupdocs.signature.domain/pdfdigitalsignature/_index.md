---
title: "فئة PdfDigitalSignature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خصائص التوقيع الرقمي PDF."
type: docs
url: /ar/python-net/groupdocs.signature.domain/pdfdigitalsignature/
is_root: false
weight: 420
---


## PdfDigitalSignature class

يمثل خصائص التوقيع الرقمي PDF.

نوع PdfDigitalSignature يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/) | يُهيئ توقيعًا رقميًا PDF دون شهادة. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store) | يُهيئ توقيعًا رقميًا PDF باستخدام مخزن X509 المحدد. سيتم استخدام الشهادة الأولى من المخزن. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#store-index) | يُهيئ توقيعًا رقميًا PDF باستخدام مخزن X509 المحدد وفهرس الشهادة. |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/#certificate) | يُهيئ توقيعًا رقميًا PDF باستخدام شهادة X509 المحددة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/clone/) | استنساخ نسخة توقيع PDF الرقمي. |
| [equals](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals/#obj) | يقارن خصائص التوقيع لتحديد المساواة. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/get_hash_code/) | يتجاوز طريقة GetHashCode. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | تحميل التواقيع الرقمية من جميع مخازن شهادات X509 النظامية. (موروث من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) | (موروث من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) | (موروث من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) | (موروث من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [contact_info](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/contact_info/) | معلومات الاتصال التي يقدمها الموقع لتمكين المستلم من التحقق من التوقيع، مثل رقم هاتف. |
| [location](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/location/) | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [reason](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/reason/) | سبب التوقيع، مثل (أوافق). |
| [show_properties](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/show_properties/) | العلم الذي يجبر خصائص التوقيع على الظهور أو الإخفاء؛ عندما تكون true، يستخدم حقل التوقيع تنسيق مظهر محدد مسبقًا (مثال، `Digitally signed by {PdfDigitalSignature.contact_info} Date: {Date} Reason: {PdfDigitalSignature.reason} Location: {PdfDigitalSignature.location}`) ويكون القيمة الافتراضية True. |
| [time_stamp](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/time_stamp/) | الطابع الزمني لتوقيع PDF الرقمي. القيمة الافتراضية هي None. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/type/) | نوع توقيع PDF الرقمي. |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | شهادة X509 المرتبطة بالتوقيع الرقمي. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | اسم المخزن المخصص للشهادة. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | موقع المخزن للشهادة. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | اسم المخزن للشهادة. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | تعليق هدف التوقيع. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | تاريخ إنشاء التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | ارتفاع التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | العلم الذي يشير إلى ما إذا كان هذا المكوّن يمثل توقيعًا (`True`) أو محتوى مستند (`False`). (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | التوقيع الرقمي صالح ولم يتم العبث بالمستند. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | الموضع الأيسر للتوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | تاريخ تعديل التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | رقم الصفحة التي تم العثور على التوقيع فيها. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | وقت توقيع المستند. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | المعرّف الفريد للتوقيع، يُستخدم لتعديل التوقيع في المستند عبر عمليات التحديث أو الحذف. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | نوع التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | بصمة شهادة. (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | الموضع العلوي للتوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | عرض التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | نوع XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). (موروثة من [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)) |

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
