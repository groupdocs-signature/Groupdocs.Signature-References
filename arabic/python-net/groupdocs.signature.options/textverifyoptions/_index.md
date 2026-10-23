---
title: "فئة TextVerifyOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يحافظ على الخيارات للتحقق من توقيع النص في المستند."
type: docs
url: /ar/python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

يحافظ على الخيارات للتحقق من توقيع النص في المستند.

تعرف على المزيد:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

نوع TextVerifyOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | ينشئ مثيلاً جديداً من TextVerifyOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | ينشئ مثيلاً جديداً من TextVerifyOptions بنص التحقق. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | ينشئ مثيلاً جديداً من TextVerifyOptions بالنص المراد التحقق منه ونوع تنفيذ التوقيع. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | عنوان حقل النموذج للتحقق منه. إذا تم تعيينه، سيُعثر على النص فقط في حقول النماذج النصية. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | نوع حقل النموذج للتحقق؛ إذا تم تعيينه، سيُعثر على النص فقط في حقول النص. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | التحقق من نوع مطابقة النص. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | معرّف توقيع النص للتحقق. يجب أن يكون أكبر من الصفر؛ يدعم فقط مستندات PDF. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | نوع التوقيع الذي سيتم التحقق منه. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | نص التوقيع للتحقق. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | العلم الذي يشير إلى ما إذا كان يجب التحقق من كل صفحة من المستند. القيمة الافتراضية هي True. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | الإضافات الإضافية للتحقق من خيارات التوقيع البديلة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | علم الخاصية الصالحة. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | رقم صفحة المستند التي سيتم التحقق منها؛ إذا لم يتم تحديده، يتم التحقق من جميع صفحات المستند للظهور الأول (القيمة الدنيا هي 1). (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | خيارات الصفحة لتحديد الصفحات التي سيتم التحقق منها. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | موضع الشكل في تخطيط المستند المستخدم للتحقق من التوقيعات في رؤوس/تذييلات الصفحات. (موروث من [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Guides
دليل المهام الذي يستخدم `TextVerifyOptions`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
