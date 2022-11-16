---
title: DigitalFormFieldSignature
second_title: GroupDocs.Signature لمرجع .NET API
description: يحتوي على خصائص حقل نموذج إدخال التوقيع الرقمي لمستندات Pdf.
type: docs
weight: 130
url: /ar/net/groupdocs.signature.domain/digitalformfieldsignature/
---
## DigitalFormFieldSignature class

يحتوي على خصائص حقل نموذج إدخال التوقيع الرقمي لمستندات Pdf.

```csharp
public sealed class DigitalFormFieldSignature : FormFieldSignature
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DigitalFormFieldSignature](digitalformfieldsignature)(string) | ينشئ PdfDigitalFormFieldSignature باسم محدد مسبقًا. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | الحصول على تاريخ إنشاء التوقيع أو تعيينه. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. يتم استخدام هذه الخاصية فقط لسجلات سجل المستند للاحتفاظ بقائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل على علامة أو اضبطها للإشارة إلى ما إذا كان هذا المكون هو توقيع أم محتوى مستند. يتم استخدام هذه الخاصية مع طريقة التحديث لتعيين العنصر كتوقيع (صواب) أو عنصر مستند (خطأ) . |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع . |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | الحصول على تاريخ تعديل التوقيع أو تعيينه. |
| [Name](../../groupdocs.signature.domain/formfieldsignature/name) { get; set; } | تحديد اسم حقل نموذج فريد . |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد أن توقيع الصفحة الذي تم العثور عليه في . |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف التوقيع الفريد لتعديل التوقيع في المستند عبر طرق التحديث أو الحذف . سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء أسلوب التسجيل أو البحث . إذا تم حفظ هذه الخاصية قبل أن يتم تعيينها يدويًا لمعالجة التوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [Signed](../../groupdocs.signature.domain/digitalformfieldsignature/signed) { get; } | خاصية للقراءة فقط توضح ما إذا كان توقيع حقل النموذج قد تم توقيعه بشهادة رقمية. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد أعلى موضع للتوقيع . |
| [Type](../../groupdocs.signature.domain/formfieldsignature/type) { get; } | يحدد نوع حقل النموذج . |
| [Value](../../groupdocs.signature.domain/formfieldsignature/value) { get; set; } | يحدد كائن بيانات حقل النموذج. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/digitalformfieldsignature/clone)() | مثيل توقيع الحقل Clone Form |
| override [Equals](../../groupdocs.signature.domain/digitalformfieldsignature/equals)(object) | طريقة الكتابة فوق يساوي لمقارنة خصائص التوقيع |
| override [GetHashCode](../../groupdocs.signature.domain/digitalformfieldsignature/gethashcode)() | يلغي طريقة GetHashCode |

### أنظر أيضا

* class [FormFieldSignature](../formfieldsignature)
* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->