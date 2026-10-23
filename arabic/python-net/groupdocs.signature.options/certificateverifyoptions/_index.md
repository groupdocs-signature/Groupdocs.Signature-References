---
title: "فئة CertificateVerifyOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحافظ على خيارات التحقق من مستندات الشهادة."
type: docs
url: /ar/python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

يحافظ على خيارات التحقق من مستندات الشهادة.

اعرف المزيد

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

يعرض نوع CertificateVerifyOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | ينشئ مثيلاً جديداً من TextVerifyOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | ينشئ كائنًا جديدًا من CertificateVerifyOptions مع الموضوع المراد التحقق منه. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | تشير الخاصية إلى ما إذا كانت الشهادة منتهية الصلاحية بناءً على نتيجة التحقق. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | جهة إصدار الشهادة المراد التحقق منها. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | نوع مطابقة النص المستخدم في التحقق. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | يجب أن توفر عملية التحقق التحقق من سلسلة X.509 باستخدام سياسة التحقق الأساسية. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | الرقم التسلسلي للشهادة المراد التحقق منه. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | موضوع الشهادة المراد التحقق منه. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | بصمة الشهادة المراد التحقق منها. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان يجب التحقق من كل صفحة من المستند. القيمة الافتراضية هي True. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | الإضافات الإضافية للتحقق من خيارات التوقيع البديلة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | علم الخاصية الصالحة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | رقم صفحة المستند التي سيتم التحقق منها؛ إذا لم يتم تحديده، يتم التحقق من جميع صفحات المستند للظهور الأول (القيمة الدنيا هي 1). (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | موضع الشكل في تخطيط المستند المستخدم للتحقق من التوقيعات في رؤوس/تذييلات الصفحات. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
