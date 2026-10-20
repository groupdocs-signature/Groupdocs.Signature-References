---
title: "TextSignOptions"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يمثل خيارات توقيع النص."
type: docs
weight: 2020
url: /ar/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

يمثل خيارات توقيع النص.

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | يُهيئ نسخة جديدة من فئة TextSignOptions بالقيم الافتراضية. |
| [TextSignOptions](textsignoptions#constructor_1)(string) | يُهيئ نسخة جديدة من فئة TextSignOptions بالنص. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | ضع التوقيع على جميع صفحات المستند. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | يحصل أو يعيّن إعدادات خلفية التوقيع. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | حدد إعدادات الحدود |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل أو عيّن نوع المستند لخيارات التوقيع [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | يحصل أو يعيّن خط التوقيع. |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | يحصل أو يضبط اللون الأمامي للتوقيع. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | يحصل أو يعيّن عنوان حقل النموذج النصي لوضع التوقيع النصي فيه. يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | يحصل أو يعيّن نوع حقل النموذج لوضع التوقيع النصي فيه. يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField. القيمة الافتراضية هي AllTextTypes. |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | يحصل أو يعيّن خوارزمية التجزئة التي ستُستخدم للعمليات التشفيرية. مدعومة حصريًا للتوقيعات الرقمية في ملفات PDF. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | ارتفاع التوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات راجع خاصية [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | الموضع X الأيسر للتوقيع على صفحة المستند بوحدات القياس (بكسل، نسب مئوية أو مليمترات انظر [`MeasureType`](../../groupdocs.signature.domain/measuretype) الخاصية LocationMeasureType). (يعمل إذا لم يتم تحديد المحاذاة الأفقية). |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | نوع القياس (بكسل، نسب مئوية أو مليمترات) للخصائص Left و Top. |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | يحصل أو يعيّن المسافة بين التوقيع وحواف المستند. (يعمل فقط إذا تم تحديد المحاذاة الأفقية أو العمودية). |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | يحصل أو يعيّن نوع القياس (بكسل، نسب مئوية أو مليمترات) للهوامش. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | يحصل أو يضبط السمة الأصلية. إذا تم ضبطها يمكن استخدام توقيعات خاصة بالمستند. العلامة المائية النصية الأصلية لمستندات WordProcessing تختلف عن العادية، على سبيل المثال. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | يحصل أو يعيّن رقم صفحة المستند للتوقيع. الحد الأدنى والقيمة الافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات التي سيتم توقيعها. |
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

* Basic usage of creating Text electronic signature by GroupDocs.Signature: [How to eSign document with Text signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* Advanced usage of settings of Text electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Text signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### انظر أيضًا

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
