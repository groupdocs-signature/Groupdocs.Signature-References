---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature لـ .NET مرجع API"
description: "يحتوي على خصائص توقيع Pdf لبيانات التعريف."
type: docs
weight: 860
url: /ar/net/groupdocs.signature.domain/pdfmetadatasignature/
---
## PdfMetadataSignature class

يحتوي على خصائص توقيع Pdf لبيانات التعريف.

```csharp
public sealed class PdfMetadataSignature : MetadataSignature
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfMetadataSignature](pdfmetadatasignature#constructor)(string) | ينشئ توقيع بيانات تعريف PDF مع اسم محدد مسبقًا وقيمة فارغة |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_1)(string, object) | ينشئ توقيع بيانات تعريف PDF مع قيم محددة مسبقًا |
| [PdfMetadataSignature](pdfmetadatasignature#constructor_2)(string, object, string) | ينشئ توقيع بيانات تعريف PDF مع قيم محددة مسبقًا |

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
| [TagPrefix](../../groupdocs.signature.domain/pdfmetadatasignature/tagprefix) { get; set; } | علامة البادئة لاسم توقيع بيانات تعريف PDF. بشكل افتراضي تُعيّن هذه الخاصية إلى "xmp". القيم الممكنة هي |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | يحدد الموضع العلوي للتوقيع. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | يحدد نوع قيمة بيانات التعريف. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | يحدد كائن بيانات التعريف. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | يحدد عرض التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone_1)() | استنساخ نسخة من توقيع بيانات التعريف. |
| override [Clone](../../groupdocs.signature.domain/pdfmetadatasignature/clone#clone)(object) | استنساخ نسخة من توقيع بيانات تعريف PDF بالقيمة المحددة. |
| override [Equals](../../groupdocs.signature.domain/pdfmetadatasignature/equals)(object) | يكتب فوق طريقة Equals لمقارنة خصائص التوقيع |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | احصل على كائن من قيمة توقيع بيانات التعريف عبر عملية فك التسلسل. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | احصل على كائن من نص توقيع بيانات التعريف عبر عملية فك التسلسل. |
| override [GetHashCode](../../groupdocs.signature.domain/pdfmetadatasignature/gethashcode)() | يكتب فوق طريقة GetHashCode |
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
| override [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)() | يحول إلى String مع طريقة تجاوز ToString() |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | يحول إلى String بالتنسيق المحدد |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string, IFormatProvider) | يحول إلى String بالتنسيق المحدد |

### انظر أيضًا

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
