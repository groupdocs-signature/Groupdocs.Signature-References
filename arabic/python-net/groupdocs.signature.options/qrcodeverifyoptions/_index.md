---
title: "الفئة QrCodeVerifyOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحفظ خيارات للتحقق من توقيع QR-code للمستند."
type: docs
url: /ar/python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 490
---


## QrCodeVerifyOptions class

يحفظ خيارات للتحقق من توقيع QR-code للمستند.

- Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document
- Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures

يعرض نوع QrCodeVerifyOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/) | يُهيئ خيارات التحقق لتواقيع QR-Code. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text) | يُهيئ خيارات التحقق لتواقيع QR-Code بالنص المحدد لرمز QR. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#text-encode_type) | يُهيئ خيارات التحقق لتواقيع QR-Code بالنص ونوع ترميز QR-Code للتحقق. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption/) | تنفيذ [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) المستخدم لتشفير وفك تشفير خصائص نص توقيع QR-Code. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type/) | التحقق من نوع QR-code. هذه الخاصية اختيارية. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان يجب التحقق من كل صفحة من المستند. القيمة الافتراضية هي True. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | الإضافات الإضافية للتحقق من خيارات التوقيع البديلة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | عنوان حقل النموذج الذي سيتم التحقق منه. إذا تم تعيينه، سيُعثر على النص فقط في حقول النموذج النصية. (موروث من [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | نوع حقل النموذج الذي سيتم التحقق منه؛ إذا تم تعيينه، سيُعثر على النص فقط في حقول النموذج النصية. (موروث من [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | علم الخاصية الصالحة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | التحقق من نوع مطابقة النص. (موروث من [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | رقم صفحة المستند التي سيتم التحقق منها؛ إذا لم يتم تحديده، يتم التحقق من جميع صفحات المستند للظهور الأول (القيمة الدنيا هي 1). (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | موضع الشكل في تخطيط المستند المستخدم للتحقق من التوقيعات في رؤوس/تذييلات الصفحات. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | معرّف توقيع النص للتحقق منه. يجب أن يكون أكبر من الصفر؛ مدعوم فقط لمستندات PDF. (موروث من [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | نوع التوقيع الذي سيتم التحقق منه. (موروث من [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | نص التوقيع للتحقق منه. (موروث من [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

def verify_qr_codes():
    with Signature("signed.pdf") as signature:
        options = QrCodeVerifyOptions()
        options.all_pages = True
        options.text = "John"
        options.match_type = TextMatchType.CONTAINS

        result = signature.verify(options)

        if result.is_valid:
            print(f"Document verified: {len(result.succeeded)} matching QR code signature(s).")
        else:
            print("Document verification failed.")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
