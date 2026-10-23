---
title: "فئة CertificateSearchOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات البحث لتوقيعات بيانات شهادة التعريف."
type: docs
url: /ar/python-net/groupdocs.signature.options/certificatesearchoptions/
is_root: false
weight: 60
---


## CertificateSearchOptions class

يمثل خيارات البحث لتوقيعات بيانات شهادة التعريف.

اعرف المزيد

- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: Advanced search within Digital Certificate X509 documents (https://docs.groupdocs.com/display/signaturenet/advanced+search+certificate+documents)

يعرض نوع CertificateSearchOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/) | ينشئ مثيلاً جديداً من فئة TextSearchOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/__init__/#text) | يُنشئ مثلاً جديداً من فئة TextSearchOptions بقيمة النص. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [match_type](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/match_type/) | نوع مطابقة النص المستخدم في البحث. |
| [text](/signature/python-net/groupdocs.signature.options/certificatesearchoptions/text/) | نص خاصية الشهادة للمطابقة أثناء البحث. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان سيتم البحث في كل صفحة من المستند. بشكل افتراضي تكون القيمة True. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | رقم صفحة المستند للبحث (اختياري). (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | الخيارات لتحديد الصفحات للبحث عن التوقيع. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | العلم الذي يشير إلى ما إذا كان سيتم إرجاع موضع الشكل في تخطيط المستند. متاح فقط لمستندات Word. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | العلم لإرجاع فقط التوقيعات المعلَّمة بـ `IsSignature`. بشكل افتراضي تكون القيمة `False`، مما يعني أنه يتم إرجاع جميع التوقيعات التي تطابق المعايير المحددة. (موروث من [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
