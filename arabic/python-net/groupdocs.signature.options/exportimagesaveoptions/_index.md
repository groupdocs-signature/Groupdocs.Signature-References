---
title: "فئة ExportImageSaveOptions"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يمثل خيارات حفظ لتصدير المستندات إلى صورة."
type: docs
url: /ar/python-net/groupdocs.signature.options/exportimagesaveoptions/
is_root: false
weight: 160
---


## ExportImageSaveOptions class

يمثل خيارات حفظ لتصدير المستندات إلى صورة.

يُظهر نوع ExportImageSaveOptions الأعضاء التالية:

### المُنشئات
| المُنشئ | الوصف |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/) | يُهيئ مثيلًا جديدًا من فئة ExportAsImageSaveOptions بالقيم الافتراضية. |
| [__init__](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/__init__/#file_format) | يُنشئ مثيلاً جديدًا من ExportAsImageSaveOptions بالتنسيق المحدد للملف. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [border](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/border/) | إعدادات حدود الصورة. بشكل افتراضي لا يتم تعيين هذه القيمة. |
| [export_all_pages](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/export_all_pages/) | العلم لتصدير كل صفحة. |
| [page_columns](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_columns/) | عدد الأعمدة للصور المصدرة. استخدم هذه الخاصية إذا كنت بحاجة لوضع الصور في صف. |
| [page_number](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/page_number/) | رقم صفحة المستند للتصدير (القيمة الدنيا هي 1). |
| [pages_setup](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/pages_setup/) | الخيارات لتحديد الصفحات التي سيتم توقيعها. |
| [tiff_multipage](/signature/python-net/groupdocs.signature.options/exportimagesaveoptions/tiff_multipage/) | صفحات المستند توضع في إطارات مختلفة داخل صورة TIFF. |
| [add_missing_extenstion](/signature/python-net/groupdocs.signature.options/saveoptions/add_missing_extenstion/) | العلم الذي يحدد ما إذا كان يجب إضافة امتداد تلقائيًا عندما يكون مفقودًا في مسار ملف الإخراج. القيمة الافتراضية هي False. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [file_format](/signature/python-net/groupdocs.signature.options/imagesaveoptions/file_format/) | تنسيق ملف المستند الموقّع. (موروث من [`ImageSaveOptions`](/signature/python-net/groupdocs.signature.options/imagesaveoptions/)) |
| [overwrite_existing_files](/signature/python-net/groupdocs.signature.options/saveoptions/overwrite_existing_files/) | العلم الذي يشير إلى ما إذا كان يجب استبدال ملف موجود بالملف الناتج الجديد. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [password](/signature/python-net/groupdocs.signature.options/saveoptions/password/) | كلمة المرور المستخدمة لحماية المستند الموقّع المحفوظ. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |
| [use_original_password](/signature/python-net/groupdocs.signature.options/saveoptions/use_original_password/) | العلم الذي يشير إلى ما إذا كان يجب استخدام كلمة المرور من [`LoadOptions`](/signature/python-net/groupdocs.signature.options/loadoptions/) عند حفظ المستند الموقّع محميًا. القيمة الافتراضية هي True. غير مدعومة للمستندات الصورة. (موروث من [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/)) |

### انظر أيضًا
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
