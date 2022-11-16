---
title: ColorResolution
second_title: GroupDocs.Signature لمرجع .NET API
description: الحصول على دقة ألوان GIF أو تعيينها.
type: docs
weight: 30
url: /ar/net/groupdocs.signature.options/gifsaveoptions/colorresolution/
---
## GifSaveOptions.ColorResolution property

الحصول على دقة ألوان GIF أو تعيينها.

```csharp
public byte ColorResolution { get; set; }
```

### ملاحظات

دقة اللون - عدد وحدات البت لكل لون أساسي متاح للصورة الأصلية ، ناقص 1. تمثل هذه القيمة حجم اللوحة بأكملها بدءًا من التي تم تحديد الألوان الموجودة في الرسم ، وليس عدد الألوان الفعلي المستخدمة في الرسم. على سبيل المثال ، إذا كانت القيمة في هذا الحقل هي 3 ، فعندئذٍ تحتوي لوحة ألوان الصورة الأصلية على 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب تعيين هذه القيمة للإشارة إلى ثراء اللوحة الأصلية ، حتى لو لم يكن كل لون من اللوحة بأكملها متاحًا على الجهاز المصدر.

### أنظر أيضا

* class [GifSaveOptions](../../gifsaveoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../gifsaveoptions)
* المجسم [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->