---
title: "فئة DigitalSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث للتوقيعات الرقمية."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

يمثل خيارات البحث للتوقيعات الرقمية.

اعرف المزيد

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

يعرض نوع DigitalSearchOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | يقوم بتهيئة نسخة جديدة من فئة DigitalSearchOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | تعليقات التوقيع الرقمي للبحث. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | الاسم المميز لمُصدر الشهادة للبحث عنه عندما لا تكون القيمة فارغة. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | نطاق التاريخ والوقت للتوقيع الرقمي للبحث. سيتم تجاهل القيمة القابلة للفراغ. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | نهاية نطاق التاريخ والوقت للتوقيعات الرقمية للبحث. سيتم تجاهل القيمة الفارغة. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | الاسم المميز للموضوع في الشهادة للبحث عنه عندما يتم توفير قيمة غير فارغة. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
