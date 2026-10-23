---
title: "فئة DocumentResultSignature"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل نتيجة معالجة عملية توقيع مستند أرشيف لمستند يحتوي على توقيعات تم إنشاؤها حديثًا."
type: docs
url: /ar/python-net/groupdocs.signature.domain/documentresultsignature/
is_root: false
weight: 170
---


## DocumentResultSignature class

يمثل نتيجة معالجة عملية توقيع مستند أرشيف لمستند يحتوي على توقيعات تم إنشاؤها حديثًا.

اعرف المزيد

- More about signing documents withing archives using GroupDocs.Signature: https://docs.groupdocs.com/signature/net/signing-archive-documents/

يعرض نوع DocumentResultSignature الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/basesignature/clone/) | نسخ نسخة التوقيع. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [equals](/signature/python-net/groupdocs.signature.domain/basesignature/equals/) | يقارن كائن التوقيع المعطى مع هذه النسخة للتحقق من المساواة. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [equals_object](/signature/python-net/groupdocs.signature.domain/basesignature/equals_object/) | (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/basesignature/get_hash_code/) | يوفر تنفيذًا مُعاد تعريفه للدالة GetHashCode. (موروث من [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/documentresultsignature/destin_document_size/) | حجم المستند الوجهة. |
| [error_message](/signature/python-net/groupdocs.signature.domain/documentresultsignature/error_message/) | رسالة الخطأ عند معالجة المستند بوجود خطأ. |
| [failed](/signature/python-net/groupdocs.signature.domain/documentresultsignature/failed/) | قائمة التوقيعات التي فشلت أثناء العملية [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [file_name](/signature/python-net/groupdocs.signature.domain/documentresultsignature/file_name/) | اسم ملف المستند. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/documentresultsignature/processing_time/) | وقت تنفيذ العملية بالمللي ثانية. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/documentresultsignature/source_document_size/) | حجم المستند المصدر. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/documentresultsignature/succeeded/) | قائمة التواقيع التي تمت معالجتها بنجاح [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/documentresultsignature/total_signatures/) | الإجمالي الكلي للتوقيعات المعالجة. |
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

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
