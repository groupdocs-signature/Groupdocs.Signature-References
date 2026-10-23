---
title: "فئة LoadOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "تسمح فئة LoadOptions بتحديد خيارات إضافية (مثل كلمة المرور) عند فتح مستند للتوقيع."
type: docs
url: /ar/python-net/groupdocs.signature.options/loadoptions/
is_root: false
weight: 300
---


## LoadOptions class

تسمح فئة LoadOptions بتحديد خيارات إضافية (مثل كلمة المرور) عند فتح مستند للتوقيع.

عيّن سمة `password` إلى كلمة مرور المستند إذا كان الملف مشفراً.

يعرض نوع LoadOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/) | يُنشئ مثلاً جديداً من فئة LoadOptions. |
| [__init__](/signature/python-net/groupdocs.signature.options/loadoptions/__init__/#file_type) | يُنشئ مثلاً جديداً من فئة [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) بنوع ملف محدد. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_type](/signature/python-net/groupdocs.signature.options/loadoptions/file_type/) | نوع الملف المرتبط بخيارات التحميل، ويكون افتراضياً [`FileType.unknown`](/signature/python-net/groupdocs.signature.domain/filetype/unknown/). |
| [load_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/load_external_resources/) | العلم الذي يحدد ما إذا كان المستند يحمل الموارد الخارجية. هذه الخاصية مهجورة؛ استخدم [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) بدلاً منها، والتي لها معنى عكسي. |
| [password](/signature/python-net/groupdocs.signature.options/loadoptions/password/) | كلمة المرور المستخدمة لفتح مستند محمي ولحفظ مستند موقّع كحماية. |
| [permissions](/signature/python-net/groupdocs.signature.options/loadoptions/permissions/) | أذونات مستند PDF مثل الطباعة، التعديل واستخراج البيانات. فقط لمستندات PDF. |
| [skip_external_resources](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) | العلم الذي يمنع المستند من تحميل الموارد الخارجية. القيمة الافتراضية هي True؛ لا يتم تحميل الموارد الخارجية إلا تلك التي تتطابق مع [`LoadOptions.WhitelistedResources`](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/). |
| [whitelisted_resources](/signature/python-net/groupdocs.signature.options/loadoptions/whitelisted_resources/) | قائمة أجزاء العناوين للموارد الخارجية التي يتم تحميلها حتى عندما يكون [`LoadOptions.SkipExternalResources`](/signature/python-net/groupdocs.signature.options/loadoptions/skip_external_resources/) صحيحًا. القيمة الافتراضية هي قائمة فارغة. |

### مثال

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import LoadOptions

load_options = LoadOptions()
load_options.password = "1234567890"
with Signature("protected.pdf", load_options) as signature:
    info = signature.get_document_info()
    print(f"{info.file_type.file_format}, {info.page_count} page(s), {info.size} bytes")
```

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
