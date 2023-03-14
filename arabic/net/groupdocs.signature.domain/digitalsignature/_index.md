---
title: DigitalSignature
second_title: GroupDocs.Signature لمرجع .NET API
description: يحتوي على خصائص التوقيع الرقمي .
type: docs
weight: 150
url: /ar/net/groupdocs.signature.domain/digitalsignature/
---
## DigitalSignature class

يحتوي على خصائص التوقيع الرقمي .

```csharp
public class DigitalSignature : BaseSignature
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)() | تهيئة التوقيع الرقمي بالمعلمات الافتراضية. |
| [DigitalSignature](digitalsignature#constructor_4)(string) | تهيئة التوقيع الرقمي باستخدام معرف التوقيع المعروف. |
| [DigitalSignature](digitalsignature#constructor_1)(X509Certificate2) | إنشاء توقيع رقمي بشهادة محددة. |
| [DigitalSignature](digitalsignature#constructor_2)(X509Store) | إنشاء توقيع رقمي بناءً على متجر X509 المحدد. سيتم استخدام الشهادة الأولى من المتجر المحدد. |
| [DigitalSignature](digitalsignature#constructor_3)(X509Store, int) | إنشاء توقيع رقمي بناءً على متجر X509 المحدد وفهرس الشهادة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Certificate](../../groupdocs.signature.domain/digitalsignature/certificate) { get; set; } | الحصول على أو تعيين شهادة X509 . |
| [CertificateStoreLocation](../../groupdocs.signature.domain/digitalsignature/certificatestorelocation) { get; set; } | يحدد موقع مخزن الشهادة |
| [CertificateStoreName](../../groupdocs.signature.domain/digitalsignature/certificatestorename) { get; set; } | يحدد اسم مخزن الشهادة . |
| [Comments](../../groupdocs.signature.domain/digitalsignature/comments) { get; set; } | الحصول على تعليق غرض التوقيع أو تعيينه. |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | الحصول على تاريخ إنشاء التوقيع أو تعيينه. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. يتم استخدام هذه الخاصية فقط لسجلات سجل المستند للاحتفاظ بقائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل على علامة أو اضبطها للإشارة إلى ما إذا كان هذا المكون هو توقيع أم محتوى مستند. يتم استخدام هذه الخاصية مع طريقة التحديث لتعيين العنصر كتوقيع (صواب) أو عنصر مستند (خطأ) . |
| [IsValid](../../groupdocs.signature.domain/digitalsignature/isvalid) { get; set; } | يظل صحيحًا إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع . |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | الحصول على تاريخ تعديل التوقيع أو تعيينه. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد أن توقيع الصفحة الذي تم العثور عليه في . |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف التوقيع الفريد لتعديل التوقيع في المستند عبر طرق التحديث أو الحذف . سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء أسلوب التسجيل أو البحث . إذا تم حفظ هذه الخاصية قبل أن يتم تعيينها يدويًا لمعالجة التوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [SignTime](../../groupdocs.signature.domain/digitalsignature/signtime) { get; set; } | الحصول على أو تعيين الوقت الذي تم فيه توقيع المستند. |
| [Thumbprint](../../groupdocs.signature.domain/digitalsignature/thumbprint) { get; } | الحصول على بصمة الشهادة. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد أعلى موضع للتوقيع . |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |
| [XAdESType](../../groupdocs.signature.domain/digitalsignature/xadestype) { get; } | نوع XAdES[`XAdESType`](./xadestype) . القيمة الافتراضية هي بلا (XAdES معطلة) . في هذه اللحظة ، يتم دعم نوع توقيع XAdES فقط لمستندات جدول البيانات. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalsignature/clone)() | مثيل استنساخ توقيع الرمز الشريطي . |
| override [Equals](../../groupdocs.signature.domain/digitalsignature/equals)(object) | طريقة الكتابة فوق يساوي لمقارنة خصائص التوقيع |
| override [GetHashCode](../../groupdocs.signature.domain/digitalsignature/gethashcode)() | يلغي طريقة GetHashCode |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures)() | تحميل التوقيع الرقمي من جميع متاجر شهادات النظام X509. |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_1)(StoreName) | تحميل التوقيع الرقمي من متجر الشهادات X509 الذي تم تمريره . |
| static [LoadDigitalSignatures](../../groupdocs.signature.domain/digitalsignature/loaddigitalsignatures#loaddigitalsignatures_2)(StoreName, StoreLocation) | تحميل التوقيع الرقمي من متجر الشهادات X509 الذي تم تمريره . |

### أنظر أيضا

* class [BaseSignature](../basesignature)
* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
