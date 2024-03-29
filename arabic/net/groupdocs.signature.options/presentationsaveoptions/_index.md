---
title: PresentationSaveOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: خيارات الحفظ لمستندات العرض التقديمي .
type: docs
weight: 1570
url: /ar/net/groupdocs.signature.options/presentationsaveoptions/
---
## PresentationSaveOptions class

خيارات الحفظ لمستندات العرض التقديمي .

```csharp
public class PresentationSaveOptions : SaveOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | تهيئة مثيل جديد لفئة PresentationSaveOptions بالقيم الافتراضية. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(bool) | تهيئة مثيل جديد لفئة PresentationSaveOptions بنوع الإخراج المحدد والكتابة فوق العلامة. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_2)(PresentationSaveFileFormat) | تهيئة مثيل جديد لفئة PresentationSaveOptions بتنسيق ملف الإخراج المحدد. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_3)(PresentationSaveFileFormat, bool) | تهيئة مثيل جديد لفئة PresentationSaveOptions بتنسيق ملف الإخراج المحدد والكتابة فوق العلامة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | الحصول على علامة أو تعيينها لإضافة الامتداد تلقائيًا عندما تكون مفقودة في مسار ملف الإخراج القيمة الافتراضية هي false . |
| [FileFormat](../../groupdocs.signature.options/presentationsaveoptions/fileformat) { get; set; } | الحصول على تنسيق ملف المستند الموقع أو تعيينه. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | يحصل أو يحدد ما إذا كان سيتم الكتابة فوق الملف الموجود بملف الإخراج الجديد. وإلا فسيتم إنشاء ملف جديد برقم كلاحقة. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | الحصول على كلمة المرور أو تعيينها لحفظ المستند الموقع بحماية كلمة المرور . هذه الخاصية غير مدعومة لمستندات الصورة. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | الحصول على أو تعيين ما إذا كان سيتم استخدام كلمة المرور من LoadOptions لحفظ المستند الموقع كمحمي. القيمة الافتراضية هي true . هذه الخاصية غير مدعومة لمستندات الصورة. |

### أنظر أيضا

* class [SaveOptions](../saveoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
