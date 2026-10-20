---
title: "StampSignOptions"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يمثل خيارات توقيع الطابع."
type: docs
weight: 2000
url: /ar/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

يمثل خيارات توقيع الطابع.

```csharp
public class StampSignOptions : ImageSignOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | يقوم بإنشاء نسخة جديدة من الفئة StampSignOptions بالقيم الافتراضية. |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | يقوم بإنشاء نسخة جديدة من الفئة StampSignOptions بخيارات المحاذاة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | ضع التوقيع على جميع صفحات المستند. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي. |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | يحصل أو يضبط خلفية Stamp. |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | يحصل أو يضبط نوع قص لون الخلفية للتوقيع. |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | يحصل أو يضبط نوع قص صورة الخلفية للتوقيع. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | حدد إعدادات الحدود |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل أو عيّن نوع المستند لخيارات التوقيع [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | يحصل أو يعيّن خوارزمية التجزئة التي ستُستخدم للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | ارتفاع التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات؛ راجع [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | يحصل أو يعيّن مسار ملف صورة التوقيع. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | يحصل أو يعيّن تدفق صورة التوقيع. إذا تم تحديد هذه الخاصية فستُستَخدم دائمًا بدلاً من ImageFilePath. |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | قائمة الخطوط الداخلية المعروضة كمجموعة من المستطيلات. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | الموضع X الأيسر للتوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الأفقية). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | يحصل أو يعيّن المسافة بين التوقيع وحواف المستند. (يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | يحصل أو يعيّن نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | قائمة الخطوط الخارجية المعروضة كدوائر متحدة المركز. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | يحصل أو يعيّن رقم صفحة المستند للتوقيع. الحد الأدنى والقيمة الافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | مستطيل المنطقة لوضع الصورة على المستند. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | يحدد مكان عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو ملليمترات) لخصائص Width و Height. |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | يحصل أو يضبط نوع الطابع. القيمة الافتراضية هي دائرية. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | وضع التمدد على Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | الموضع Y العلوي للتوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة العمودية). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | يحصل أو يعيّن شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | محاذاة عمودية للتوقيع على صفحة المستند. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية أو مليمترات [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | يحصل أو يعيّن موضع Z-order لتوقيع النص. يحدد ترتيب عرض التواقيع المتداخلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | يمسح الموارد الداخلية |

### ملاحظات

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### انظر أيضًا

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
