---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يحتوي على خصائص توقيع Pdf الرقمي."
type: docs
weight: 840
url: /ar/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

يحتوي على خصائص توقيع Pdf الرقمي.

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | تهيئة توقيع PDF الرقمي بدون شهادة. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | إنشاء توقيع PDF الرقمي باستخدام شهادة محددة. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | تهيئة توقيع PDF الرقمي بناءً على مخزن X509 المحدد. سيتم استخدام الشهادة الأولى من المخزن المحدد. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | إنشاء توقيع PDF الرقمي بناءً على مخزن X509 المحدد وفهرس الشهادة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | يحصل أو يعيّن شهادة X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | يحدد اسم المخزن المخصص للشهادة. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | يحدد موقع المخزن للشهادة |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | يحدد اسم المخزن للشهادة. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | يحصل أو يعيّن تعليق هدف التوقيع. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | المعلومات التي يقدمها المُوقّع لتمكين المستلم من الاتصال بالمُوقّع للتحقق من التوقيع، مثل رقم هاتف. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | احصل أو عيّن تاريخ إنشاء التوقيع. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلامة التي تشير إلى ما إذا تم حذف هذا التوقيع من المستند. تُستخدم هذه الخاصية فقط لسجلات سجل تاريخ المستند للحفاظ على قائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل أو عيّن علامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى مستند. تُستخدم هذه الخاصية مع طريقة Update لتعيين العنصر كتوقيع (صحيح) أو كعنصر مستند (خطأ). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | يبقى صحيحًا إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع. |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | احصل أو عيّن تاريخ تعديل التوقيع. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد الصفحة التي تم العثور على التوقيع فيها. |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | سبب التوقيع، مثل (I agreeРІР‚В¦). |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | فرض إظهار/إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا، يكون حقل التوقيع له تنسيق مظهر محدد مسبقًا: موقّع رقمياً بواسطة {[`ContactInfo`](./contactinfo)} التاريخ: {Date} السبب: {[`Reason`](./reason)} الموقع: {[`Location`](./location)} ShowProperties يكون صحيحًا بشكل افتراضي. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف فريد للتوقيع لتعديل التوقيع في المستند عبر طريقتي Update أو Delete. سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء طريقة Sign أو Search. إذا تم حفظ هذه الخاصية مسبقًا يمكن تعيينها يدويًا للتلاعب بالتوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | يحصل أو يعيّن وقت توقيع المستند. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | يحصل على بصمة الشهادة. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | الطابع الزمني لتوقيع PDF الرقمي. القيمة الافتراضية هي null. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد الموضع العلوي للتوقيع. |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | نوع توقيع PDF الرقمي. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | نوع XAdES [`XAdESType`](../digitalsignature/xadestype). القيمة الافتراضية هي None (XAdES غير مفعّل). في الوقت الحالي، نوع توقيع XAdES مدعوم فقط للمستندات من نوع Spreadsheet. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | استنساخ كائن توقيع الباركود. |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | يكتب فوق طريقة Equals لمقارنة خصائص التوقيع |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | يكتب فوق طريقة GetHashCode |

### انظر أيضًا

* class [DigitalSignature](../digitalsignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
