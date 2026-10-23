---
title: "فئة DigitalVBA"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل التوقيع الرقمي لمشروعات VBA في جداول البيانات."
type: docs
url: /ar/python-net/groupdocs.signature.domain.extensions/digitalvba/
is_root: false
weight: 60
---


## DigitalVBA class

يمثل التوقيع الرقمي لمشروعات VBA في جداول البيانات.

يوفر القدرة على توقيع مشروع VBA في صيغ مستندات الجداول مثل `Xlsm` أو `Xltm`. إذا تم إضافة عدة امتدادات [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/) إلى [`DigitalSignOptions.extensions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)، يُستخدم الأول فقط أثناء التوقيع.

نوع DigitalVBA يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_file_path-password) | يُنشئ مثيلاً جديدًا من الفئة DigitalVBA باستخدام ملف شهادة. |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/#certificate_stream-password) | يُنشئ مثيلاً جديدًا من الفئة DigitalVBA باستخدام تدفق شهادة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/) | يحصل على نسخة من هذا الكائن. (موروث من [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [certificate_file_path](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_file_path/) | مسار ملف الشهادة الرقمية، يُستخدم فقط إذا لم يتم تحديد `CertificateStream`. |
| [certificate_stream](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/certificate_stream/) | تدفق الشهادة الرقمية. إذا تم تحديد هذه الخاصية فسيتم دائمًا استخدامها بدلاً من CertificateFilePath. |
| [comments](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/comments/) | تعليقات التوقيع. |
| [password](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/password/) | كلمة مرور الشهادة الرقمية. |
| [sign_only_vba_project](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/sign_only_vba_project/) | الإعداد الذي يحدد ما إذا كان سيتم توقيع مشروع VBA فقط. عندما يكون True، لا يتم توقيع مستند الجدول نفسه؛ يتم توقيع مشروع VBA فقط. |

### مثال

```python
import zipfile
from groupdocs.signature import Signature
from groupdocs.signature.domain.extensions import DigitalVBA
from groupdocs.signature.options import DigitalSignOptions


def sign_spreadsheet_macros_only():
    # توقيع الماكرو داخل الجدول
    with Signature("sample.xlsm") as signature:
        sign_options = DigitalSignOptions()

        # إضافة امتداد لتوقيع مشروع VBA رقمياً
        digital_vba = DigitalVBA("certificate.pfx", "1234567890")
        digital_vba.sign_only_vba_project = True
        digital_vba.comments = "Signed VBA macros"
        sign_options.extensions.append(digital_vba)

        result = signature.sign("signed_macros.xlsm", sign_options)
        print(f"Signatures added: {len(result.succeeded)}")

    # تحقق من أنه تم إضافة جزء توقيع مشروع VBA
    with zipfile.ZipFile("signed_macros.xlsm") as package:
        print("VBA project signed:", "xl/vbaProjectSignature.bin" in package.namelist())
```

### انظر أيضًا
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
