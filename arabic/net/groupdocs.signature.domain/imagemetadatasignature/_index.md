---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يحتوي على خصائص توقيع بيانات تعريف الصورة."
type: docs
weight: 740
url: /ar/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

يحتوي على خصائص توقيع بيانات تعريف الصورة.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | ينشئ Image Metadata Signature مع المعرف والقيمة |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | احصل أو عيّن تاريخ إنشاء التوقيع. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | يحصل أو يعيّن تنفيذ واجهة [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) لتشفير وفك تشفير خصائص قيمة التوقيع. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلامة التي تشير إلى ما إذا تم حذف هذا التوقيع من المستند. تُستخدم هذه الخاصية فقط لسجلات سجل تاريخ المستند للحفاظ على قائمة التوقيعات المحذوفة. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | قيمة للقراءة فقط للحصول على وصف لتوقيع بيانات الصورة القياسي |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | معرف توقيع بيانات الصورة. انظر فئة ImageMetadataSignatures التي تحتوي على توقيع قياسي مع قيمة معرف مسبقة. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل أو عيّن علامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى مستند. تُستخدم هذه الخاصية مع طريقة Update لتعيين العنصر كتوقيع (صحيح) أو كعنصر مستند (خطأ). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | احصل أو عيّن تاريخ تعديل التوقيع. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | يحدد اسم بيانات التعريف الفريد. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد الصفحة التي تم العثور على التوقيع فيها. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف فريد للتوقيع لتعديل التوقيع في المستند عبر طريقتي Update أو Delete. سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء طريقة Sign أو Search. إذا تم حفظ هذه الخاصية مسبقًا يمكن تعيينها يدويًا للتلاعب بالتوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | قيمة للقراءة فقط للحصول على حجم قيمة البيانات الوصفية |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد الموضع العلوي للتوقيع. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | يحدد نوع قيمة بيانات التعريف. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | يحدد كائن بيانات التعريف. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | استنساخ نسخة من توقيع بيانات التعريف. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | استنساخ كائن توقيع بيانات الصورة بالقيمة المعطاة. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | يكتب فوق طريقة Equals لمقارنة خصائص التوقيع |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | احصل على كائن من قيمة توقيع بيانات التعريف عبر عملية فك التسلسل. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | احصل على كائن من نص توقيع بيانات التعريف عبر عملية فك التسلسل. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | يكتب فوق طريقة GetHashCode |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | يحول إلى قيمة منطقية. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | يحول إلى DateTime. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | يحول إلى DateTime. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | يحول إلى Decimal. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | يحول إلى Decimal. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | يحول إلى Double. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | يحول إلى Double. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | يحول إلى integer. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | يحوّل إلى نوع long. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | يحول إلى float. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | يحول إلى float. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | يحول إلى String مع طريقة تجاوز ToString() |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | يحول إلى String بالتنسيق المحدد |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | يحول إلى String بالتنسيق المحدد |

### انظر أيضًا

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
