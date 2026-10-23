---
title: "الفئة JpegSaveOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات حفظ JPEG للمستندات الصورية."
type: docs
url: /ar/python-net/groupdocs.signature.options/jpegsaveoptions/
is_root: false
weight: 290
---


## JpegSaveOptions class

يمثل خيارات حفظ JPEG للمستندات الصورية.

يعرض نوع JpegSaveOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/__init__/) | يقوم بتهيئة JpegSaveOptions بالقيم الافتراضية. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bits_per_channel](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/bits_per_channel/) | عدد البتات لكل قناة في صورة JPEG غير مضغوطة. القيم المدعومة تتراوح من 2 إلى 8 بتات لكل قناة. |
| [color_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/color_type/) | نوع اللون لصورة JPEG. |
| [comment](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/comment/) | تعليق ملف JPEG. |
| [compression_type](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/compression_type/) | نوع الضغط. |
| [quality](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/quality/) | جودة الصورة. |
| [sample_rounding_mode](/signature/python-net/groupdocs.signature.options/jpegsaveoptions/sample_rounding_mode/) | وضع تقريب العينة المستخدم لتناسب قيمة 8‑بت مع قيمة n‑بت من `JpegOptions.BitsPerChannel`. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | العلم الذي يحدد ما إذا كان يجب إضافة امتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي False. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | تنسيق ملف المستند الموقّع. (موروث من [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | العلم الذي يشير إلى ما إذا كان يجب استبدال ملف موجود بالملف الناتج الجديد. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | كلمة المرور المستخدمة لحماية المستند الموقّع المحفوظ. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | العلم الذي يشير إلى ما إذا كان يجب استخدام كلمة المرور من [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) عند حفظ المستند الموقّع محميًا. القيمة الافتراضية هي True. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
