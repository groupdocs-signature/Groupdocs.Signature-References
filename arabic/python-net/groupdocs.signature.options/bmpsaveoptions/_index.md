---
title: "الفئة BmpSaveOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات حفظ BMP لمستندات الصور."
type: docs
url: /ar/python-net/groupdocs.signature.options/bmpsaveoptions/
is_root: false
weight: 50
---


## BmpSaveOptions class

يمثل خيارات حفظ BMP لمستندات الصور.

نوع BmpSaveOptions يكشف عن الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/__init__/) | يُهيئ BmpSaveOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bits_per_pixel](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/bits_per_pixel/) | عدد بتات الصورة لكل بكسل. |
| [compression](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/compression/) | الضغط. راجع `BitmapCompression`. |
| [horizontal_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/horizontal_resolution/) | الدقة الأفقية. لاحظ أن نتيجة التقريب قد تجعل الدقة الناتجة تختلف قليلًا عن القيمة المحددة. |
| [vertical_resolution](/signature/python-net/groupdocs.signature.options/bmpsaveoptions/vertical_resolution/) | الدقة العمودية؛ لاحظ أن نتيجة التقريب قد تجعل الدقة الناتجة تختلف قليلًا عن القيمة المحددة. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | العلم الذي يحدد ما إذا كان يجب إضافة امتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي False. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | تنسيق ملف المستند الموقّع. (موروث من [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | العلم الذي يشير إلى ما إذا كان يجب استبدال ملف موجود بالملف الناتج الجديد. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | كلمة المرور المستخدمة لحماية المستند الموقّع المحفوظ. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | العلم الذي يشير إلى ما إذا كان يجب استخدام كلمة المرور من [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) عند حفظ المستند الموقّع محميًا. القيمة الافتراضية هي True. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
