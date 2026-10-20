---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يمثل خيارات التوقيع الرقمي."
type: docs
weight: 1560
url: /ar/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

يمثل خيارات التوقيع الرقمي.

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بالقيم الافتراضية. |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بتدفق الشهادة. |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بملف الشهادة. |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بتدفق الشهادة وتدفق الصورة. |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بتدفق الشهادة وملف الصورة. |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بملف الشهادة وتدفق الصورة. |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | ينشئ مثيلاً جديداً من الفئة DigitalSignOptions بملف الشهادة وملف الصورة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | يحصل أو يضبط علامة تسمح بالتوقيع باستخدام شهادة انتهت فترة صلاحيتها. القيمة الافتراضية هي false: التوقيع بشهادة منتهية الصلاحية يرمي [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception)، ولا يتم توقيع المستند. |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | يحصل أو يضبط علامة تسمح بالتوقيع باستخدام شهادة لم يبدأ بعد فترة صلاحيتها. القيمة الافتراضية هي false: التوقيع بهذه الشهادة يرمي [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception)، ولا يتم توقيع المستند. |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | ضع التوقيع على جميع صفحات المستند. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | حدد إعدادات الحدود |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | يحصل أو يضبط مسار ملف الشهادة الرقمية. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد CertificateStream. |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | يحصل أو يضبط تدفق الشهادة الرقمية. إذا تم تحديد هذه الخاصية، يتم استخدامها دائماً بدلاً من CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | يحصل أو يضبط جهة اتصال التوقيع. |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | يحصل أو يضبط دالة تجزئة توقيع مخصصة، مما يسمح للمستخدمين بتنفيذ منطق التوقيع الرقمي الخاص بهم. يتيح ذلك التوقيع باستخدام شهادات خارجية ويدعم خوارزميات تجزئة مختلفة. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل أو عيّن نوع المستند لخيارات التوقيع [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | يحصل أو يعيّن خوارزمية التجزئة التي ستُستخدم للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | ارتفاع التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات؛ راجع [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | يحصل أو يعيّن مسار ملف صورة التوقيع. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد ImageStream. |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | يحصل أو يعيّن تدفق صورة التوقيع. إذا تم تحديد هذه الخاصية فستُستَخدم دائمًا بدلاً من ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | الموضع X الأيسر للتوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الأفقية). |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | يحصل أو يعيّن موقع التوقيع. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top. |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | يحصل أو يعيّن المسافة بين التوقيع وحواف المستند. (يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | يحصل أو يعيّن نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | يحصل أو يعيّن رقم صفحة المستند للتوقيع. الحد الأدنى والقيمة الافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | يحصل أو يعيّن كلمة مرور الشهادة الرقمية. |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | يحصل أو يعيّن سبب التوقيع. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | مستطيل المنطقة لوضع الصورة على المستند. |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | يحدد مكان عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | يحصل أو يعيّن خصائص التوقيع الرقمي للمستند. لتوقيع مستندات Pdf يمكن تعيين خصائص متقدمة باستخدام نسخة من [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature). |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو ملليمترات) لخصائص Width و Height. |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | وضع التمدد على Document Page. |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | الموضع Y العلوي للتوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة العمودية). |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | يحصل أو يعيّن شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم). |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | يحصل/يعيّن علم التحقق ltv (التحقق طويل الأمد). |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | محاذاة عمودية للتوقيع على صفحة المستند. |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | يحصل أو يعيّن رؤية التوقيع. |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند بقيم قياس (بكسل، نسب مئوية أو مليمترات [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | نوع XAdES [`XAdESType`](./xadestype). القيمة الافتراضية هي None (XAdES غير مفعل). في الوقت الحالي يتم دعم نوع توقيع XAdES فقط لمستندات الجداول. |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | يحصل أو يعيّن موضع Z-order لتوقيع النص. يحدد ترتيب عرض التواقيع المتداخلة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | يمسح الموارد الداخلية |

### ملاحظات

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### انظر أيضًا

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
