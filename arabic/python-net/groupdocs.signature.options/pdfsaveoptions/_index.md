---
title: "الفئة PdfSaveOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات الحفظ لمستندات PDF."
type: docs
url: /ar/python-net/groupdocs.signature.options/pdfsaveoptions/
is_root: false
weight: 340
---


## PdfSaveOptions class

يمثل خيارات الحفظ لمستندات PDF.

نوع PdfSaveOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/) | يُنشئ مثيلاً جديدًا من PdfSaveOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format) | يُنشئ مثيلاً جديدًا من PdfSaveOptions بالتنسيق المحدد لملف الإخراج. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#overwrite_existing_file) | يُنشئ مثيلاً جديدًا من PdfSaveOptions بعلم الكتابة فوق. |
| [__init__](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/__init__/#file_format-overwrite_existing_file) | يُنشئ مثيلاً جديدًا من PdfSaveOptions بالتنسيق المحدد لملف الإخراج وعلم الكتابة فوق. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/file_format/) | تنسيق الملف للمستند الموقع. |
| [permissions](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions/) | أذونات مستند PDF مثل الطباعة، والتعديل، واستخراج البيانات. |
| [permissions_password](/signature/python-net/groupdocs.signature.options/pdfsaveoptions/permissions_password/) | كلمة مرور الأذونات (كلمة المرور الأساسية) المطلوبة لتغيير إعدادات الأذونات. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | العلم الذي يحدد ما إذا كان يجب إضافة امتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي False. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | العلم الذي يشير إلى ما إذا كان يجب استبدال ملف موجود بالملف الناتج الجديد. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | كلمة المرور المستخدمة لحماية المستند الموقّع المحفوظ. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | العلم الذي يشير إلى ما إذا كان يجب استخدام كلمة المرور من [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) عند حفظ المستند الموقّع محميًا. القيمة الافتراضية هي True. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions, PdfSaveOptions, QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

load_options = LoadOptions()
load_options.password = "1234567890"

save_options = PdfSaveOptions()
save_options.password = "new-password"
save_options.permissions_password = "new-owner-password"
save_options.use_original_password = False

qr_options = QrCodeSignOptions("Approved by John Smith", QrCodeTypes.QR)

with Signature("protected.pdf", load_options) as signature:
    result = signature.sign("signed_new_password.pdf", qr_options, save_options)
    print(f"Signatures added: {len(result.succeeded)}")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
