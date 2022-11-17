---
title: PdfDigitalSignature
second_title: GroupDocs.Signature لمرجع .NET API
description: يحتوي على خصائص توقيع رقمي بتنسيق PDF .
type: docs
weight: 630
url: /ar/net/groupdocs.signature.domain/pdfdigitalsignature/
---
## PdfDigitalSignature class

يحتوي على خصائص توقيع رقمي بتنسيق PDF .

```csharp
public class PdfDigitalSignature : DigitalSignature
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfDigitalSignature](pdfdigitalsignature#constructor)() | تهيئة توقيع Pdf الرقمي بدون شهادة. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_1)(X509Certificate2) | إنشاء توقيع رقمي بتنسيق PDF بشهادة محددة. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_2)(X509Store) | تهيئة توقيع Pdf الرقمي بناءً على متجر X509 المحدد. سيتم استخدام الشهادة الأولى من المتجر المحدد. |
| [PdfDigitalSignature](pdfdigitalsignature#constructor_3)(X509Store, int) | إنشاء توقيع رقمي بتنسيق PDF استنادًا إلى مخزن X509 المحدد وفهرس الشهادة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | الحصول على أو تعيين شهادة X509 . |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | يحدد موقع مخزن الشهادة |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | يحدد اسم مخزن الشهادة . |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | الحصول على تعليق غرض التوقيع أو تعيينه. |
| [ContactInfo](../../groupdocs.signature.domain/pdfdigitalsignature/contactinfo) { get; set; } | المعلومات التي يوفرها الموقّع لتمكين المستلم من الاتصال بالموقع للتحقق من التوقيع ، على سبيل المثال رقم الهاتف. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | الحصول على تاريخ إنشاء التوقيع أو تعيينه. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. يتم استخدام هذه الخاصية فقط لسجلات سجل المستند للاحتفاظ بقائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل على علامة أو اضبطها للإشارة إلى ما إذا كان هذا المكون هو توقيع أم محتوى مستند. يتم استخدام هذه الخاصية مع طريقة التحديث لتعيين العنصر كتوقيع (صواب) أو عنصر مستند (خطأ) . |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | يظل صحيحًا إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع . |
| [Location](../../groupdocs.signature.domain/pdfdigitalsignature/location) { get; set; } | اسم مضيف وحدة المعالجة المركزية أو الموقع الفعلي للتوقيع. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | الحصول على تاريخ تعديل التوقيع أو تعيينه. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد أن توقيع الصفحة الذي تم العثور عليه في . |
| [Reason](../../groupdocs.signature.domain/pdfdigitalsignature/reason) { get; set; } | سبب التوقيع مثل (أوافق PР‚В¦) . |
| [ShowProperties](../../groupdocs.signature.domain/pdfdigitalsignature/showproperties) { get; set; } | فرض إظهار / إخفاء خصائص التوقيع. في حالة كون ShowProperties صحيحًا ، فإن التوقيع الحقل يحتوي على تنسيق محدد مسبقًا للمظهر موقع رقميًا بواسطة {[`ContactInfo`](./contactinfo)} التاريخ: {Date} السبب: {[`Reason`](./reason)} الموقع: {[`Location`](./location) } تكون ShowProperties صحيحة بشكل افتراضي . |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف التوقيع الفريد لتعديل التوقيع في المستند عبر طرق التحديث أو الحذف . سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء أسلوب التسجيل أو البحث . إذا تم حفظ هذه الخاصية قبل أن يتم تعيينها يدويًا لمعالجة التوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | الحصول على أو تعيين الوقت الذي تم فيه توقيع المستند. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | الحصول على بصمة الشهادة. |
| [TimeStamp](../../groupdocs.signature.domain/pdfdigitalsignature/timestamp) { get; set; } | الطابع الزمني للتوقيع الرقمي بتنسيق PDF . القيمة الافتراضية خالية. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد أعلى موضع للتوقيع . |
| [Type](../../groupdocs.signature.domain/pdfdigitalsignature/type) { get; set; } | نوع التوقيع الرقمي بتنسيق PDF . |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | نوع XAdES[`XAdESType`](../digitalsignature/xadestype) . القيمة الافتراضية هي بلا (XAdES معطلة) . في هذه اللحظة ، يتم دعم نوع توقيع XAdES فقط لمستندات جدول البيانات. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfdigitalsignature/clone)() | مثيل استنساخ توقيع الرمز الشريطي . |
| override [Equals](../../groupdocs.signature.domain/pdfdigitalsignature/equals)(object) | طريقة الكتابة فوق يساوي لمقارنة خصائص التوقيع |
| override [GetHashCode](../../groupdocs.signature.domain/pdfdigitalsignature/gethashcode)() | يلغي طريقة GetHashCode |

### أنظر أيضا

* class [DigitalSignature](../digitalsignature)
* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
