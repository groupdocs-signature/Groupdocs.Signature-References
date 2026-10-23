---
title: "الفئة DigitalVerifyOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحافظ على خيارات التحقق من التوقيع الرقمي للمستند."
type: docs
url: /ar/python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

يحافظ على خيارات التحقق من التوقيع الرقمي للمستند.

اعرف المزيد

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

نوع DigitalVerifyOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | يُهيئ مثيل DigitalVerifyOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | يُهيئ مثيل DigitalVerifyOptions بمسار ملف الشهادة الرقمية المحدد. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | يُهيئ مثيل DigitalVerifyOptions بتدفق الشهادة المحدد. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | شهادة X509Certificate2 المستخرجة من مسار ملف الشهادة أو التدفق. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | مسار ملف الشهادة الرقمية. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | تدفق الشهادة الرقمية. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | تعليقات التوقيع الرقمي للتحقق منها. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | جهة اتصال التوقيع للتحقق منها. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | اسم مصدر الشهادة للتحقق منه. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | موقع التوقيع للتحقق منه. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | كلمة مرور الشهادة الرقمية إذا كانت مطلوبة. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | سبب التوقيع الرقمي للتحقق منه. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | بداية نطاق التاريخ والوقت للتوقيع الرقمي للتحقق منه. سيتم تجاهل القيمة None. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | نهاية نطاق التاريخ والوقت للتوقيع الرقمي للتحقق منه. سيتم تجاهل القيمة null. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | الاسم المميز للموضوع في الشهادة للتحقق منها؛ تتحقق عملية التحقق مما إذا كان اسم موضوع التوقيع يحتوي على هذه القيمة أو يساويها مع مراعاة حساسية الحالة. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان يجب التحقق من كل صفحة من المستند. القيمة الافتراضية هي True. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | الإضافات الإضافية للتحقق من خيارات التوقيع البديلة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | علم الخاصية الصالحة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | رقم صفحة المستند التي سيتم التحقق منها؛ إذا لم يتم تحديده، يتم التحقق من جميع صفحات المستند للظهور الأول (القيمة الدنيا هي 1). (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | موضع الشكل في تخطيط المستند المستخدم للتحقق من التوقيعات في رؤوس/تذييلات الصفحات. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
