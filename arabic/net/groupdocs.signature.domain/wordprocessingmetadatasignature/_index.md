---
title: "WordProcessingMetadataSignature"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يحتوي على خصائص توقيع بيانات تعريف معالجة النصوص."
type: docs
weight: 1260
url: /ar/net/groupdocs.signature.domain/wordprocessingmetadatasignature/
---
## WordProcessingMetadataSignature class

يحتوي على خصائص توقيع بيانات تعريف معالجة النصوص.

```csharp
public sealed class WordProcessingMetadataSignature : MetadataSignature
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor)(string) | ينشئ WordProcessing Metadata Signature مع اسم محدد مسبقًا وقيمة فارغة. |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor_1)(string, object) | ينشئ WordProcessing Metadata Signature مع قيم محددة مسبقًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | احصل أو عيّن تاريخ إنشاء التوقيع. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | يحصل أو يعيّن تنفيذ واجهة [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) لتشفير وفك تشفير خصائص قيمة التوقيع. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | احصل على العلامة التي تشير إلى ما إذا تم حذف هذا التوقيع من المستند. تُستخدم هذه الخاصية فقط لسجلات سجل تاريخ المستند للحفاظ على قائمة التوقيعات المحذوفة. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | يحدد ارتفاع التوقيع. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | احصل أو عيّن علامة لتحديد ما إذا كان هذا المكوّن توقيعًا أم محتوى مستند. تُستخدم هذه الخاصية مع طريقة Update لتعيين العنصر كتوقيع (صحيح) أو كعنصر مستند (خطأ). |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | يحدد الموضع الأيسر للتوقيع. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | احصل أو عيّن تاريخ تعديل التوقيع. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | يحدد اسم بيانات التعريف الفريد. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | يحدد الصفحة التي تم العثور على التوقيع فيها. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | معرّف فريد للتوقيع لتعديل التوقيع في المستند عبر طريقتي Update أو Delete. سيتم تعيين هذه الخاصية تلقائيًا بعد استدعاء طريقة Sign أو Search. إذا تم حفظ هذه الخاصية مسبقًا يمكن تعيينها يدويًا للتلاعب بالتوقيع. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | يحدد نوع التوقيع. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد الموضع العلوي للتوقيع. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | يحدد نوع قيمة بيانات التعريف. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | يحدد كائن بيانات التعريف. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone_1)() | استنساخ نسخة من توقيع بيانات التعريف. |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone)(object) | استنساخ نسخة من توقيع بيانات الكلمات الوصفية بالقيمة المحددة. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | يكتب فوق طريقة Equals لمقارنة خصائص التوقيع |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | احصل على كائن من قيمة توقيع بيانات التعريف عبر عملية فك التسلسل. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | احصل على كائن من نص توقيع بيانات التعريف عبر عملية فك التسلسل. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | يكتب فوق طريقة GetHashCode |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | يحول إلى قيمة منطقية. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | يحول إلى DateTime. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | يحول إلى DateTime. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | يحول إلى Decimal. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | يحول إلى Decimal. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | يحول إلى Double. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | يحول إلى Double. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | يحول إلى integer. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | يحول إلى float. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | يحول إلى float. |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring)() | يحول إلى String مع طريقة تجاوز ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | يحول إلى String بالتنسيق المحدد |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | يحول إلى String بالتنسيق المحدد |

### انظر أيضًا

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
