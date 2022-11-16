---
title: ImageMetadataSignature
second_title: GroupDocs.Signature لمرجع .NET API
description: يحتوي على خصائص توقيع بيانات تعريف الصورة.
type: docs
weight: 550
url: /ar/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

يحتوي على خصائص توقيع بيانات تعريف الصورة.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | إنشاء توقيع بيانات وصفية للصورة بالمعرف والقيمة |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | الحصول على تاريخ إنشاء التوقيع أو تعيينه. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | يحصل أو يحدد تنفيذ[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) واجهة لتشفير وفك تشفير خصائص قيمة التوقيع. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلم الذي يشير إلى ما إذا كان هذا التوقيع قد تم حذفه من المستند. يتم استخدام هذه الخاصية فقط لسجلات سجل المستند للاحتفاظ بقائمة التوقيعات المحذوفة. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | قيمة للقراءة فقط للحصول على وصف لتوقيع البيانات الوصفية للصورة القياسي |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | معرف توقيع بيانات تعريف الصورة. راجعImageMetadataSignatures فئة تحتوي على توقيع قياسي بقيمة معرّف محددة مسبقًا. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل على علامة أو اضبطها للإشارة إلى ما إذا كان هذا المكون هو توقيع أم محتوى مستند. يتم استخدام هذه الخاصية مع طريقة التحديث لتعيين العنصر كتوقيع (صواب) أو عنصر مستند (خطأ) . |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع . |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | الحصول على تاريخ تعديل التوقيع أو تعيينه. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | يحدد اسم البيانات الوصفية الفريد . |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد أن توقيع الصفحة الذي تم العثور عليه في . |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف التوقيع الفريد لتعديل التوقيع في المستند عبر طرق التحديث أو الحذف . سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء أسلوب التسجيل أو البحث . إذا تم حفظ هذه الخاصية قبل أن يتم تعيينها يدويًا لمعالجة التوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | قيمة للقراءة فقط للحصول على حجم قيمة البيانات الوصفية |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد أعلى موضع للتوقيع . |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | تحديد كائن البيانات الوصفية . |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | مثيل توقيع بيانات تعريف النسخ . |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | مثيل توقيع البيانات الوصفية لصورة النسخ بقيمة معينة. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | طريقة الكتابة فوق يساوي لمقارنة خصائص التوقيع |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | الحصول على كائن من قيمة توقيع البيانات الوصفية عبر إلغاء التسلسل. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | الحصول على كائن من نص توقيع البيانات الوصفية عبر إلغاء التسلسل. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | يلغي طريقة GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | تحويل إلى قيمة منطقية . |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | التحويل إلى DateTime . |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | التحويل إلى DateTime . |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | تحويل إلى عشري . |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | تحويل إلى عشري . |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | تحويل إلى Double . |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | تحويل إلى Double . |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | تحويل إلى عدد صحيح . |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | تحويل إلى طويل. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | تحويل إلى عائم . |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | تحويل إلى عائم . |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | التحويل إلى سلسلة مع تجاوز ToString () method |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | تحويل إلى سلسلة بالتنسيق المحدد |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | تحويل إلى سلسلة بالتنسيق المحدد |

### أنظر أيضا

* class [MetadataSignature](../metadatasignature)
* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
