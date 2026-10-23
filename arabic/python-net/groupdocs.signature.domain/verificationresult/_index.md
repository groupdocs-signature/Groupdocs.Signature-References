---
title: "فئة VerificationResult"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل كائنًا يحتفظ بنتائج عملية التحقق."
type: docs
url: /ar/python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

يمثل كائنًا يحتفظ بنتائج عملية التحقق.

يعرض نوع VerificationResult الأعضاء التالية:

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | حجم المستند الوجهة. للتحقق، هذا المتغيّر دائمًا يحتوي على الصفر. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | قائمة التوقيعات التي فشلت في عملية التحقق. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | نتيجة التحقق؛ True إذا كانت عملية التحقق ناجحة، وإلا False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | وقت تنفيذ العملية بالمللي ثانية. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | حجم المستند المصدر بالبايت. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | قائمة التوقيعات التي تم التحقق منها بنجاح [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | الإجمالي الكلي للتوقيعات المعالجة. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### انظر أيضًا
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
