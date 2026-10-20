---
title: "التوقيع الرقمي"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يحتوي على خصائص التوقيع الرقمي."
type: docs
weight: 150
url: /ar/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

يحتوي على خصائص التوقيع الرقمي.

```csharp
public class DigitalSignature : BaseSignature
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | تهيئة التوقيع الرقمي بالمعلمات الافتراضية. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | تهيئة التوقيع الرقمي بمعرف SignatureId المعروف. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | إنشاء توقيع رقمي بشهادة محددة. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | إنشاء توقيع رقمي استنادًا إلى مخزن X509 المحدد. سيتم استخدام أول شهادة من المخزن المحدد. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | إنشاء توقيع رقمي استنادًا إلى مخزن X509 المحدد وفهرس الشهادة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | يحصل أو يعيّن شهادة X509. |
| [CertificateCustomStoreName](../../groupdocs.signature.domain/digitalsignature/certificatecustomstorename) { get; set; } | يحدد اسم المخزن المخصص للشهادة. |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | يحدد موقع المخزن للشهادة |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | يحدد اسم المخزن للشهادة. |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | يحصل أو يعيّن تعليق هدف التوقيع. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | احصل أو عيّن تاريخ إنشاء التوقيع. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلامة التي تشير إلى ما إذا تم حذف هذا التوقيع من المستند. تُستخدم هذه الخاصية فقط لسجلات سجل تاريخ المستند للحفاظ على قائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل أو عيّن علامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى مستند. تُستخدم هذه الخاصية مع طريقة Update لتعيين العنصر كتوقيع (صحيح) أو كعنصر مستند (خطأ). |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | يبقى صحيحًا إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | احصل أو عيّن تاريخ تعديل التوقيع. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد الصفحة التي تم العثور على التوقيع فيها. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف فريد للتوقيع لتعديل التوقيع في المستند عبر طريقتي Update أو Delete. سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء طريقة Sign أو Search. إذا تم حفظ هذه الخاصية مسبقًا يمكن تعيينها يدويًا للتلاعب بالتوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | يحصل أو يعيّن وقت توقيع المستند. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | يحصل على بصمة الشهادة. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد الموضع العلوي للتوقيع. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | نوع XAdES [`XAdESType`](./xadestype). القيمة الافتراضية هي None (XAdES غير مفعل). في الوقت الحالي يتم دعم نوع توقيع XAdES فقط لمستندات الجداول. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | استنساخ كائن توقيع الباركود. |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | يكتب فوق طريقة Equals لمقارنة خصائص التوقيع |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | يكتب فوق طريقة GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | تحميل التواقيع الرقمية من جميع مخازن شهادات X509 النظامية. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | تحميل التواقيع الرقمية من مخزن شهادة. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_3)(string) | تحميل التواقيع الرقمية من مخزن شهادة. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | تحميل التواقيع الرقمية من مخزن شهادة رقمية موجود في موقع محدد. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_4)(string, StoreLocation) | تحميل التواقيع الرقمية من مخزن شهادة رقمية موجود في موقع محدد. |

### انظر أيضًا

* class [BaseSignature](../basesignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
