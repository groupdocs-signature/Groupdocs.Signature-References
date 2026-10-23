---
title: "فئة ImageSaveOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات الحفظ للمستندات الصورية."
type: docs
url: /ar/python-net/groupdocs.signature.options/imagesaveoptions/
is_root: false
weight: 230
---


## ImageSaveOptions class

يمثل خيارات الحفظ للمستندات الصورية.

نوع ImageSaveOptions يعرض الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/) | ينشئ مثيلًا جديدًا من فئة ImagesSaveOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#overwrite_existing_file) | ينشئ مثيلًا جديدًا من فئة ImagesSaveOptions مع علم الكتابة فوق. |
| [__init__](/signature/python-net/groupdocs.signature.options/imagesaveoptions/__init__/#file_format-overwrite_existing_file) | ينشئ مثيلًا جديدًا من ImagesSaveOptions بالتنسيق المحدد لملف الإخراج وعلم الكتابة فوق. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | تنسيق الملف للمستند الموقع. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | العلم الذي يحدد ما إذا كان يجب إضافة امتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي False. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | العلم الذي يشير إلى ما إذا كان يجب استبدال ملف موجود بالملف الناتج الجديد. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | كلمة المرور المستخدمة لحماية المستند الموقّع المحفوظ. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | العلم الذي يشير إلى ما إذا كان يجب استخدام كلمة المرور من [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) عند حفظ المستند الموقّع محميًا. القيمة الافتراضية هي True. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
