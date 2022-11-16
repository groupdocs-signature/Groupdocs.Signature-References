---
title: DigitalSearchOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل خيارات البحث عن التوقيعات الرقمية.
type: docs
weight: 1250
url: /ar/net/groupdocs.signature.options/digitalsearchoptions/
---
## DigitalSearchOptions class

يمثل خيارات البحث عن التوقيعات الرقمية.

```csharp
public class DigitalSearchOptions : SearchOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DigitalSearchOptions](digitalsearchoptions)() | تهيئة مثيل جديد لفئة DigitalSearchOptions بالقيم الافتراضية. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | قم بوضع علامة للبحث في كل صفحة من صفحات المستند. بشكل افتراضي ، يتم تعيين هذه القيمة على "صحيح". |
| [Comments](../../groupdocs.signature.options/digitalsearchoptions/comments) { get; set; } | تعليقات التوقيع الرقمي للبحث . |
| [IssuerName](../../groupdocs.signature.options/digitalsearchoptions/issuername) { get; set; } | للقيم غير الفارغة يحدد الاسم المميز لجهة إصدار الشهادة للبحث. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | الحصول على رقم صفحة المستند للبحث أو تعيينه . القيمة اختيارية . |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | خيارات لتحديد صفحات للبحث في التوقيع . |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalsearchoptions/signdatetimefrom) { get; set; } | نطاق التاريخ والوقت للتوقيع الرقمي للبحث. سيتم تجاهل القيمة الفارغة. |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalsearchoptions/signdatetimeto) { get; set; } | نطاق التاريخ والوقت للتوقيع الرقمي للبحث. سيتم تجاهل القيمة الفارغة. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | قم بوضع علامة لإرجاع التوقيعات فقط التي تم وضع علامة عليها على أنها IsSignature. القيمة الافتراضية هي false التي تشير إلى إرجاع جميع التوقيعات التي تطابق المعايير المحددة. |
| [SubjectName](../../groupdocs.signature.options/digitalsearchoptions/subjectname) { get; set; } | للقيم غير الفارغة يحدد اسم الموضوع المميز للشهادة للبحث. |

### ملاحظات

**يتعلم أكثر**

* الاستخدام الأساسي للبحث عن التوقيع الإلكتروني الرقمي بواسطة GroupDocs. التوقيع: [ كيفية البحث عن التوقيعات الرقمية في مستند](https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
* الاستخدام المتقدم لإعدادات البحث عن التوقيع الإلكتروني الرقمي باستخدام GroupDocs. التوقيع: [الاستخدام المتقدم للتوقيعات الرقمية لـ eSearch في مستند وإعدادات إضافية](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

### أنظر أيضا

* class [SearchOptions](../searchoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->