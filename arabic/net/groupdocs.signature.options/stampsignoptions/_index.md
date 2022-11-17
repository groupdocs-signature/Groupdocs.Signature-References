---
title: StampSignOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل خيارات توقيع الطوابع.
type: docs
weight: 1630
url: /ar/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

يمثل خيارات توقيع الطوابع.

```csharp
public class StampSignOptions : ImageSignOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | تهيئة مثيل جديد لفئة StampSignOptions بالقيم الافتراضية. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | تهيئة مثيل جديد لفئة StampSignOptions مع خيارات المحاذاة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | ضع التوقيع على كافة صفحات المستند. يمكن استخدام هذه الخاصية فقط لتنسيقات الصور متعددة الإطارات (Tiff) . |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي . |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | الحصول على خلفية الطابع أو تعيينها. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | الحصول على أو تعيين نوع اقتصاص لون الخلفية للتوقيع. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | الحصول على أو تعيين نوع اقتصاص صورة الخلفية للتوقيع. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | تحديد إعدادات الحدود |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل على أو اضبط "نوع المستند" لخيارات التوقيع[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع . |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | ارتفاع التوقيع في صفحة المستند في قيم القياس (وحدات البكسل أو النسب المئوية أو المليمترات ترى[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) . |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | الحصول على مسار ملف صورة التوقيع أو تعيينه. يتم استخدام هذه الخاصية فقط إذا لم يتم تحديد ImageStream . |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | الحصول على دفق صورة التوقيع أو تعيينه . إذا تم تحديد هذه الخاصية ، يتم استخدامها دائمًا بدلاً من ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | قائمة الخطوط الداخلية المعروضة كمجموعة من المستطيلات. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | موضع التوقيع الأيسر X في صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) . (يعمل في حالة عدم تحديد المحاذاة الأفقية) . |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | نوع القياس (وحدات البكسل أو النسب المئوية أو المليمترات) للخصائص اليسرى والعلوية . |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | الحصول على المسافة بين حواف التوقيع والمستند أو تعيينها. (يعمل فقط في حالة تحديد المحاذاة الأفقية أو الرأسية) . |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | الحصول على نوع المقياس أو تحديده (بكسل أو نسبة مئوية أو ملليمتر) للهامش. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | قائمة الخطوط الخارجية المقدمة كدوائر متحدة المركز. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | الحصول على رقم صفحة المستند أو تعيينه للتوقيع. القيمة الدنيا والافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات المراد توقيعها. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | مستطيل مساحة لوضع الصورة في المستند. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (باتجاه عقارب الساعة). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | نوع القياس (البكسل أو النسب المئوية أو المليمترات) لخصائص العرض والارتفاع. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | الحصول على نوع الطوابع أو تعيينه. القيمة الافتراضية هي Round . |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | وضع التمدد في صفحة المستند . |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | أعلى موضع التوقيع على صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) . (يعمل في حالة عدم تحديد المحاذاة الرأسية) . |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | الحصول على شفافية التوقيع أو تعيينها (القيمة من 0.0 (معتم) إلى 1.0 (مسح)). القيمة الافتراضية هي 0 (معتمة) . |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | محاذاة رأسية للتوقيع على صفحة المستند. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند في قياس القيم (بكسل أو نسبة مئوية أو ملليمتر)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) . |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | الحصول على أو تحديد موضع ترتيب Z لتوقيع النص. لتحديد ترتيب عرض التواقيع المتداخلة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | مسح الموارد الداخلية |

### ملاحظات

**يتعلم أكثر**

* الاستخدام الأساسي لإنشاء ختم توقيع إلكتروني بواسطة GroupDocs. التوقيع: [كيفية التوقيع الإلكتروني للمستند باستخدام ختم التوقيع](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* الاستخدام المتقدم لإعدادات ختم التوقيع الإلكتروني باستخدام GroupDocs. التوقيع: [الاستخدام المتقدم لوثيقة eSign مع توقيع الطوابع وإعدادات إضافية](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### أنظر أيضا

* class [ImageSignOptions](../imagesignoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
