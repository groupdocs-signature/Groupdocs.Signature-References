---
title: "الفئة PngSaveOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "خيارات حفظ PNG للمستندات الصورية."
type: docs
url: /ar/python-net/groupdocs.signature.options/pngsaveoptions/
is_root: false
weight: 400
---


## PngSaveOptions class

خيارات حفظ PNG للمستندات الصورية.

يعرض نوع PngSaveOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/pngsaveoptions/__init__/) | ينشئ PngSaveOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bit_depth](/signature/python-net/groupdocs.signature.options/pngsaveoptions/bit_depth/) | عمق البت. |
| [color_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/color_type/) | نوع `PngColorType`. |
| [compression_level](/signature/python-net/groupdocs.signature.options/pngsaveoptions/compression_level/) | مستوى ضغط صورة PNG في النطاق من 0 إلى 9، حيث 9 هو أقصى ضغط و0 هو وضع التخزين. |
| [filter_type](/signature/python-net/groupdocs.signature.options/pngsaveoptions/filter_type/) | نوع الفلتر `PngFilterType` المستخدم أثناء عملية حفظ ملف PNG. |
| [progressive](/signature/python-net/groupdocs.signature.options/pngsaveoptions/progressive/) | العلم التدريجي الذي يشير إلى ما إذا كان PNG يتم حفظه تدريجيًا. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | العلم الذي يحدد ما إذا كان يجب إضافة امتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي False. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | تنسيق ملف المستند الموقّع. (موروث من [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | العلم الذي يشير إلى ما إذا كان يجب استبدال ملف موجود بالملف الناتج الجديد. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | كلمة المرور المستخدمة لحماية المستند الموقّع المحفوظ. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | العلم الذي يشير إلى ما إذا كان يجب استخدام كلمة المرور من [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) عند حفظ المستند الموقّع محميًا. القيمة الافتراضية هي True. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
