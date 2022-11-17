---
title: PdfMetadataSignature
second_title: GroupDocs.Signature لمرجع .NET API
description: يحتوي على خصائص توقيع بيانات تعريف Pdf .
type: docs
weight: 650
url: /ar/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

يحتوي على خصائص توقيع بيانات تعريف Pdf .

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | إنشاء توقيع بيانات تعريف Pdf باسم محدد مسبقًا وقيمة فارغة |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | إنشاء توقيع بيانات تعريف Pdf بقيم محددة مسبقًا |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | إنشاء توقيع بيانات تعريف Pdf بقيم محددة مسبقًا |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | الحصول على تاريخ إنشاء التوقيع أو تعيينه. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | يحصل أو يحدد تنفيذ[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) واجهة لتشفير وفك تشفير خصائص قيمة التوقيع. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. يتم استخدام هذه الخاصية فقط لسجلات سجل المستند للاحتفاظ بقائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل على علامة أو اضبطها للإشارة إلى ما إذا كان هذا المكون هو توقيع أم محتوى مستند. يتم استخدام هذه الخاصية مع طريقة التحديث لتعيين العنصر كتوقيع (صواب) أو عنصر مستند (خطأ) . |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع . |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | الحصول على تاريخ تعديل التوقيع أو تعيينه. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | يحدد اسم البيانات الوصفية الفريد . |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد أن توقيع الصفحة الذي تم العثور عليه في . |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف التوقيع الفريد لتعديل التوقيع في المستند عبر طرق التحديث أو الحذف . سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء أسلوب التسجيل أو البحث . إذا تم حفظ هذه الخاصية قبل أن يتم تعيينها يدويًا لمعالجة التوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | علامة البادئة لاسم توقيع بيانات تعريف Pdf. يتم تعيين هذه الخاصية افتراضيًا على "xmp" . القيم المحتملة هي |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد أعلى موضع للتوقيع . |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | تحديد كائن البيانات الوصفية . |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | مثيل توقيع بيانات تعريف النسخ . |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | مثيل توقيع بيانات التعريف Clone Pdf بقيمة معينة. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | طريقة الكتابة فوق يساوي لمقارنة خصائص التوقيع |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | الحصول على كائن من قيمة توقيع البيانات الوصفية عبر إلغاء التسلسل. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | الحصول على كائن من نص توقيع البيانات الوصفية عبر إلغاء التسلسل. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | يلغي طريقة GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | تحويل إلى قيمة منطقية . |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | التحويل إلى DateTime . |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | التحويل إلى DateTime . |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | تحويل إلى عشري . |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | تحويل إلى عشري . |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | تحويل إلى Double . |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | تحويل إلى Double . |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | تحويل إلى عدد صحيح . |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | تحويل إلى عائم . |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | تحويل إلى عائم . |
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | التحويل إلى سلسلة مع تجاوز ToString () method |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | تحويل إلى سلسلة بالتنسيق المحدد |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | تحويل إلى سلسلة بالتنسيق المحدد |

### أنظر أيضا

* class [MetadataSignature](../metadatasignature)
* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
