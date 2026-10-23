---
title: "فئة ImageDigitalVerifyOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحفظ خيارات للتحقق من التوقيعات الرقمية في الصور النقطية."
type: docs
url: /ar/python-net/groupdocs.signature.options/imagedigitalverifyoptions/
is_root: false
weight: 220
---


## ImageDigitalVerifyOptions class

يحفظ خيارات للتحقق من التوقيعات الرقمية في الصور النقطية.

نوع ImageDigitalVerifyOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/__init__/) | يُنشئ مثلاً جديداً من فئة ImageDigitalVerifyOptions للتحقق من التوقيعات الرقمية (الستيجانوغرافيا) في الصور النقطية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [detected_probability](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detected_probability/) | الاحتمالية التي تُرجعها الدالة AnalyzePercentageDigitalSignature (0-100). |
| [detection_threshold_percent](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/detection_threshold_percent/) | نسبة عتبة الكشف للاستخراج الجزئي (0-100). القيمة الافتراضية هي 75. |
| [password](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/password/) | كلمة المرور التي استُخدمت لتضمين التوقيع. |
| [use_full_data_extraction](/signature/python-net/groupdocs.signature.options/imagedigitalverifyoptions/use_full_data_extraction/) | الخاصية تحدد ما إذا كان يتم استخراج البيانات بالكامل (AnalyzePercentageDigitalSignature) لتحقيق أقصى دقة. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان يجب التحقق من كل صفحة من المستند. القيمة الافتراضية هي True. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | الإضافات الإضافية للتحقق من خيارات التوقيع البديلة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | علم الخاصية الصالحة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | رقم صفحة المستند التي سيتم التحقق منها؛ إذا لم يتم تحديده، يتم التحقق من جميع صفحات المستند للظهور الأول (القيمة الدنيا هي 1). (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | موضع الشكل في تخطيط المستند المستخدم للتحقق من التوقيعات في رؤوس/تذييلات الصفحات. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
