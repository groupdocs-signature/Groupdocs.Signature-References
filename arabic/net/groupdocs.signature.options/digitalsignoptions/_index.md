---
title: DigitalSignOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل خيارات التوقيع الرقمي.
type: docs
weight: 1340
url: /ar/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

يمثل خيارات التوقيع الرقمي.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | تهيئة مثيل جديد لفئة DigitalSignOptions بالقيم الافتراضية. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | تهيئة مثيل جديد لفئة DigitalSignOptions مع دفق الشهادة. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | تهيئة مثيل جديد لفئة DigitalSignOptions بملف الشهادة. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | تهيئة مثيل جديد لفئة DigitalSignOptions مع دفق الشهادة ودفق الصورة. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | تهيئة مثيل جديد لفئة DigitalSignOptions مع دفق الشهادة وملف الصورة. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | يقوم بتهيئة مثيل جديد لفئة DigitalSignOptions مع ملف الشهادة ودفق الصورة. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | تهيئة مثيل جديد لفئة DigitalSignOptions مع ملف الشهادة وملف الصورة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | ضع التوقيع على كافة صفحات المستند. يمكن استخدام هذه الخاصية فقط لتنسيقات الصور متعددة الإطارات (Tiff) . |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي . |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | تحديد إعدادات الحدود |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | الحصول على مسار ملف الشهادة الرقمية أو تعيينه . يتم استخدام هذه الخاصية فقط إذا لم يتم تحديد CertificateStream . |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | الحصول على دفق الشهادة الرقمية أو تعيينه . إذا تم تحديد هذه الخاصية ، يتم استخدامها دائمًا بدلاً من CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | الحصول على أو تعيين جهة اتصال التوقيع. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل على أو اضبط "نوع المستند" لخيارات التوقيع[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع . |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | ارتفاع التوقيع في صفحة المستند في قيم القياس (وحدات البكسل أو النسب المئوية أو المليمترات ترى[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) . |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | الحصول على مسار ملف صورة التوقيع أو تعيينه. يتم استخدام هذه الخاصية فقط إذا لم يتم تحديد ImageStream . |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | الحصول على دفق صورة التوقيع أو تعيينه . إذا تم تحديد هذه الخاصية ، يتم استخدامها دائمًا بدلاً من ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | موضع التوقيع الأيسر X في صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) . (يعمل في حالة عدم تحديد المحاذاة الأفقية) . |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | الحصول على أو تحديد موقع التوقيع. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | نوع القياس (وحدات البكسل أو النسب المئوية أو المليمترات) للخصائص اليسرى والعلوية . |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | الحصول على المسافة بين حواف التوقيع والمستند أو تعيينها. (يعمل فقط في حالة تحديد المحاذاة الأفقية أو الرأسية) . |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | الحصول على نوع المقياس أو تحديده (بكسل أو نسبة مئوية أو ملليمتر) للهامش. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | الحصول على رقم صفحة المستند أو تعيينه للتوقيع. القيمة الدنيا والافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات المراد توقيعها. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | الحصول على أو تعيين كلمة مرور الشهادة الرقمية. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | الحصول على أو تحديد سبب التوقيع. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | مستطيل مساحة لوضع الصورة في المستند. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (باتجاه عقارب الساعة). |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | الحصول على أو تعيين خصائص التوقيع الرقمي للمستند. لتوقيع مستندات Pdf ، من الممكن تعيين خصائص متقدمة باستخدام مثيل[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | نوع القياس (البكسل أو النسب المئوية أو المليمترات) لخصائص العرض والارتفاع. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | وضع التمدد في صفحة المستند . |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | أعلى موضع التوقيع على صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType) . (يعمل في حالة عدم تحديد المحاذاة الرأسية) . |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | الحصول على شفافية التوقيع أو تعيينها (القيمة من 0.0 (معتم) إلى 1.0 (مسح)). القيمة الافتراضية هي 0 (معتمة) . |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | محاذاة رأسية للتوقيع على صفحة المستند. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | الحصول على رؤية التوقيع أو تعيينها. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند في قياس القيم (بكسل أو نسبة مئوية أو ملليمتر)[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType) . |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | نوع XAdES[`XAdESType`](./xadestype) . القيمة الافتراضية هي بلا (XAdES معطلة) . في هذه اللحظة ، يتم دعم نوع توقيع XAdES فقط لمستندات جدول البيانات. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | الحصول على أو تحديد موضع ترتيب Z لتوقيع النص. لتحديد ترتيب عرض التواقيع المتداخلة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | مسح الموارد الداخلية |

### ملاحظات

**يتعلم أكثر**

* الاستخدام الأساسي لإنشاء توقيع إلكتروني رقمي بواسطة GroupDocs. التوقيع: [كيفية التوقيع الإلكتروني للمستند بالتوقيع الرقمي](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* الاستخدام المتقدم لإعدادات التوقيع الإلكتروني الرقمي مع GroupDocs. التوقيع: [الاستخدام المتقدم لـ eSign Document مع التوقيع الرقمي والإعدادات الإضافية](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### أنظر أيضا

* class [ImageSignOptions](../imagesignoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
