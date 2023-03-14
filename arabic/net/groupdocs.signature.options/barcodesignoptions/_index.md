---
title: BarcodeSignOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل خيارات توقيع الباركود.
type: docs
weight: 1260
url: /ar/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

يمثل خيارات توقيع الباركود.

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | تهيئة مثيل جديد لفئة BarcodeSignOptions بالقيم الافتراضية. |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | تهيئة مثيل جديد لفئة BarcodeSignOptions بالنص. |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | تهيئة مثيل جديد لفئة BarcodeSignOptions بالنص. |

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | ضع التوقيع على كل صفحات الوثيقة. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | مظهر توقيع إضافي . |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | الحصول على أو تعيين إعدادات خلفية التوقيع. |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | تحديد إعدادات الحدود |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | الحصول على محاذاة النص في صورة الرمز الشريطي الناتجة أو تعيينها. القيمة الافتراضية هي بلا. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | احصل على أو اضبط "نوع المستند" لخيارات التوقيع[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | الحصول على نوع الرمز الشريطي أو تعيينه. |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | ملحقات التوقيع . |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | الحصول على خط التوقيع أو تعيينه. |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | الحصول على اللون الأمامي لأشرطة الباركود أو تعيينه قد يتسبب استخدام هذه الخاصية في حدوث مشكلات في التحقق. استخدمه بعناية. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | الحصول على عنوان حقل نموذج النص أو تعيينه لوضع توقيع نص فيه . يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField. |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | يحصل أو يحدد نوع حقل النموذج لوضع توقيع نص فيه . يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextToFormField. القيمة افتراضيًا هي AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | ارتفاع التوقيع في صفحة المستند في قيم القياس (وحدات البكسل أو النسب المئوية أو المليمترات ترى[`MeasureType`](../../groupdocs.signature.domain/measuretype) خاصية SizeMeasureType) . |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | محاذاة أفقية للتوقيع على صفحة المستند. |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | الحصول على المسافة بين عناصر الباركود وحدود الصورة الناتجة أو تعيينها. |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | موضع التوقيع الأيسر X في صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype) خاصية LocationMeasureType) . (تعمل إذا لم يتم تحديد محاذاة أفقية) . |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | نوع القياس (وحدات البكسل أو النسب المئوية أو المليمترات) للخصائص اليسرى والعلوية . |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | الحصول على المسافة بين حواف التوقيع والمستند أو تعيينها. (يعمل فقط في حالة تحديد المحاذاة الأفقية أو الرأسية) . |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | الحصول على نوع المقياس أو تحديده (بكسل أو نسبة مئوية أو ملليمتر) للهامش. |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | الحصول على أو تعيين السمة الأصلية. إذا تم تعيينه ، فيمكن استخدام توقيعات محددة للمستند. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | الحصول على رقم صفحة المستند أو تعيينه للتوقيع. القيمة الدنيا والافتراضية هي 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | خيارات لتحديد الصفحات المراد توقيعها. |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | الحصول على علامة أو تعيينها للحصول على محتوى صورة الرمز الشريطي للتوقيع الذي تم وضعه على صفحة المستند.[`ReturnContentType`](./returncontenttype) . يتم تعطيل هذا الخيار افتراضيًا. |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | يحدد نوع الملف لمحتوى الصورة التي تم إرجاعها لتوقيع الباركود عند تمكين خاصية ReturnContent . بشكل افتراضي يتم تعيينها على Null. هذا يعني إرجاع محتوى صورة الباركود بالتنسيق الأصلي. تم تحديد تنسيق الصورة هذا على[`Format`](../../groupdocs.signature.domain/barcodesignature/format) القيم الممكنة المدعومة هي: FileType.JPEG ، FileType.PNG ، FileType.BMP. إذا كان التنسيق المقدم غير مدعوم ، فسيتم إرجاع محتوى صورة الرمز الشريطي بتنسيق .png . |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | زاوية دوران التوقيع على صفحة المستند (باتجاه عقارب الساعة). |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | الحصول على نوع الشكل لوضع نص أو تعيينه. يمكن استخدام هذه الخاصية فقط مع SignatureImplementation = TextStamp. القيمة الافتراضية هي المستطيل . |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | الحصول على أو تعيين المعرف الفريد للتوقيع. يمكن استخدامه في خيارات التحقق من التوقيع. الخاصية مدعومة لمستندات Pdf فقط. |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | الحصول على أو تحديد نوع تنفيذ توقيع النص. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | احصل على نوع التوقيع[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | نوع القياس (البكسل أو النسب المئوية أو المليمترات) لخصائص العرض والارتفاع. |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | وضع التمدد في صفحة المستند . |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | الحصول على نص التوقيع أو تعيينه. |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | المحاذاة الأفقية للنص داخل التوقيع. هذه الميزة مدعومة فقط لتطبيقات توقيع الصور والتعليقات التوضيحية (راجع[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) خاصية تنفيذ التوقيع) . |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | المحاذاة الرأسية للنص داخل التوقيع . هذه الميزة مدعومة فقط لتنفيذ توقيع الصورة (راجع[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) التوقيع على خاصية التنفيذ). |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | أعلى موضع التوقيع على صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات انظر[`MeasureType`](../../groupdocs.signature.domain/measuretype)خاصية LocationMeasureType) . (تعمل إذا لم يتم تحديد محاذاة عمودية) . |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | الحصول على شفافية التوقيع أو تعيينها (القيمة من 0.0 (معتم) إلى 1.0 (مسح)). القيمة الافتراضية هي 0 (معتمة) . |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | محاذاة رأسية للتوقيع على صفحة المستند. |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | عرض التوقيع على صفحة المستند في قياس القيم (وحدات البكسل أو النسب المئوية أو المليمترات ترى[`MeasureType`](../../groupdocs.signature.domain/measuretype) خاصية SizeMeasureType) . |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | الحصول على أو تحديد موضع ترتيب Z لتوقيع النص. لتحديد ترتيب عرض التواقيع المتداخلة. |

### ملاحظات

**يتعلم أكثر**

* الاستخدام الأساسي لإنشاء توقيع إلكتروني للرمز الشريطي بواسطة GroupDocs. التوقيع: [كيفية التوقيع الإلكتروني للمستند باستخدام توقيع الباركود](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* الاستخدام المتقدم لإعدادات التوقيع الإلكتروني للرمز الشريطي مع GroupDocs. التوقيع: [الاستخدام المتقدم للتوقيع الإلكتروني للمستند مع توقيع الباركود والإعدادات الإضافية](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### أنظر أيضا

* class [TextSignOptions](../textsignoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
