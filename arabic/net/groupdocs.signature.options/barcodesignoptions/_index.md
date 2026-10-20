---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يمثل خيارات توقيع الباركود."
type: docs
weight: 1450
url: /ar/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

يمثل خيارات توقيع الباركود.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | ينشئ مثيلًا جديدًا من الفئة BarcodeSignOptions بالقيم الافتراضية. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | ينشئ مثيلًا جديدًا من الفئة BarcodeSignOptions بالنص. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | ينشئ مثيلًا جديدًا من الفئة BarcodeSignOptions بالنص. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | ضع التوقيع على جميع صفحات المستند. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | يحصل أو يعيّن إعدادات خلفية التوقيع. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | حدد إعدادات الحدود |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | يحصل أو يعيّن محاذاة النص في صورة الباركود الناتجة. القيمة الافتراضية هي None. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل أو عيّن نوع المستند لخيارات التوقيع [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | يحصل أو يعيّن نوع الباركود. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | يحصل أو يعيّن خط التوقيع. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | يحصل أو يعيّن اللون الأمامي لأشرطة الباركود. قد يسبب استخدام هذه الخاصية مشاكل في التحقق. استخدمها بحذر. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | يحصل أو يعيّن عنوان حقل النموذج النصي لوضع التوقيع النصي فيه. يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | يحصل أو يعيّن نوع حقل النموذج لوضع التوقيع النصي فيه. يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField. القيمة الافتراضية هي AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | يحصل أو يعيّن خوارزمية التجزئة التي ستُستخدم للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | ارتفاع التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات راجع خاصية [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | يحصل أو يعيّن المسافة بين عناصر الباركود وحدود الصورة الناتجة. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | الموضع X الأيسر للتوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) الخاصية LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الأفقية). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | يحصل أو يعيّن المسافة بين التوقيع وحواف المستند. (يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | يحصل أو يعيّن نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | يحصل أو يضبط السمة الأصلية. إذا تم ضبطها يمكن استخدام توقيعات خاصة بالمستند. العلامة المائية النصية الأصلية لمستندات WordProcessing تختلف عن العادية، على سبيل المثال. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | يحصل أو يعيّن رقم صفحة المستند للتوقيع. الحد الأدنى والقيمة الافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات التي سيتم توقيعها. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | يحصل أو يضبط العلامة للحصول على محتوى صورة الباركود لتوقيع تم وضعه على صفحة المستند. إذا تم ضبط هذه العلامة على true، سيحتفظ محتوى صورة توقيع الباركود ببيانات الصورة الخام بالتنسيق المطلوب [`ReturnContentType`](./returncontenttype). بشكل افتراضي هذا الخيار معطل. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | يحدد نوع الملف لمحتوى الصورة المعاد لتوقيع الباركود عندما تكون الخاصية ReturnContent مفعلة. بشكل افتراضي يتم تعيينه إلى Null. وهذا يعني إرجاع محتوى صورة الباركود بالتنسيق الأصلي. يتم تحديد تنسيق الصورة هذا في [`Format`](../../groupdocs.signature.domain/barcodesignature/format). القيم المدعومة الممكنة هي: FileType.JPEG، FileType.PNG، FileType.BMP. إذا كان التنسيق المقدم غير مدعوم فسيتم إرجاع محتوى صورة الباركود بتنسيق .png. |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (مع اتجاه عقارب الساعة). |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | يحدد مكان عرض الشكل في تخطيط المستند. متاح فقط لمستندات Word. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | يحصل أو يضبط نوع الشكل لإضافة النص. يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextStamp. القيمة الافتراضية هي Rectangle. |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | يحصل أو يضبط المعرف الفريد للتوقيع. يمكن استخدامه في خيارات التحقق من التوقيع. الخاصية مدعومة فقط لمستندات Pdf. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | يحصل أو يضبط نوع تنفيذ توقيع النص. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو ملليمترات) لخصائص Width و Height. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | وضع التمدد على Document Page. |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | يحصل أو يضبط نص التوقيع. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | محاذاة النص أفقياً داخل التوقيع. هذه الميزة مدعومة فقط لتطبيقات توقيع Image و Annotation (انظر الخاصية SignatureImplementation في [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | محاذاة النص رأسياً داخل التوقيع. هذه الميزة مدعومة فقط لتطبيق توقيع Image (انظر الخاصية SignatureImplementation في [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | الموضع Y العلوي للتوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) الخاصية LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الرأسية). |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | يحصل أو يعيّن شفافية التوقيع (قيمة من 0.0 (معتم) إلى 1.0 (شفاف)). القيمة الافتراضية هي 0 (معتم). |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | محاذاة عمودية للتوقيع على صفحة المستند. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) الخاصية SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | يحصل أو يعيّن موضع Z-order لتوقيع النص. يحدد ترتيب عرض التواقيع المتداخلة. |

### ملاحظات

**Learn more**

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### انظر أيضًا

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
