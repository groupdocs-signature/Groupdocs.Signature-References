---
title: ImageSignOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل خيارات توقيع الصورة.
type: docs
weight: 1340
url: /ar/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

يمثل خيارات توقيع الصورة.

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | تهيئة مثيل جديد لفئة ImageSignOptions بالقيم الافتراضية. |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | تهيئة مثيل جديد لفئة ImageSignOptions مع تدفق الصورة. |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | تهيئة مثيل جديد لفئة ImageSignOptions مع ملف الصورة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | ضع التوقيع على كافة صفحات المستند. يمكن استخدام هذه الخاصية فقط لتنسيقات الصور متعددة الإطارات (Tiff) . |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي . |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | تحديد إعدادات الحدود |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل على أو اضبط "نوع المستند" لخيارات التوقيع[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع . |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | ارتفاع التوقيع في صفحة المستند في قيم القياس (وحدات البكسل أو النسب المئوية أو المليمترات ترى[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) . |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | الحصول على مسار ملف صورة التوقيع أو تعيينه. يتم استخدام هذه الخاصية فقط إذا لم يتم تحديد ImageStream . |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | الحصول على دفق صورة التوقيع أو تعيينه . إذا تم تحديد هذه الخاصية ، يتم استخدامها دائمًا بدلاً من ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | موضع التوقيع الأيسر X في صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) . (يعمل في حالة عدم تحديد المحاذاة الأفقية) . |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | نوع القياس (وحدات البكسل أو النسب المئوية أو المليمترات) للخصائص اليسرى والعلوية . |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | الحصول على المسافة بين حواف التوقيع والمستند أو تعيينها. (يعمل فقط في حالة تحديد المحاذاة الأفقية أو الرأسية) . |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | الحصول على نوع المقياس أو تحديده (بكسل أو نسبة مئوية أو ملليمتر) للهامش. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | الحصول على رقم صفحة المستند أو تعيينه للتوقيع. القيمة الدنيا والافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات المراد توقيعها. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | مستطيل مساحة لوضع الصورة في المستند. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (باتجاه عقارب الساعة). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | نوع القياس (البكسل أو النسب المئوية أو المليمترات) لخصائص العرض والارتفاع. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | وضع التمدد في صفحة المستند . |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | أعلى موضع التوقيع على صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) . (يعمل في حالة عدم تحديد المحاذاة الرأسية) . |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | الحصول على شفافية التوقيع أو تعيينها (القيمة من 0.0 (معتم) إلى 1.0 (مسح)). القيمة الافتراضية هي 0 (معتمة) . |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | محاذاة رأسية للتوقيع على صفحة المستند. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند في قياس القيم (بكسل أو نسبة مئوية أو ملليمتر)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) . |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | الحصول على أو تحديد موضع ترتيب Z لتوقيع النص. لتحديد ترتيب عرض التواقيع المتداخلة. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | إنشاء مثيل جديد لفئة ImageSignOptions مع صورة محددة مسبقًا من Base64. |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | مسح الموارد الداخلية |

### ملاحظات

**يتعلم أكثر**

* الاستخدام الأساسي لإنشاء توقيع إلكتروني للصورة بواسطة GroupDocs. التوقيع: [كيفية التوقيع الإلكتروني للمستند مع توقيع الصورة](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* الاستخدام المتقدم لإعدادات التوقيع الإلكتروني للصور مع GroupDocs. التوقيع: [الاستخدام المتقدم لوثيقة eSign مع توقيع الصورة والإعدادات الإضافية](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### أنظر أيضا

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
