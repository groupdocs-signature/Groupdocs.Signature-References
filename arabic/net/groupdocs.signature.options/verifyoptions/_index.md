---
title: VerifyOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يحتفظ بالخيارات للتحقق من المستند.
type: docs
weight: 1780
url: /ar/net/groupdocs.signature.options/verifyoptions/
---
## VerifyOptions class

يحتفظ بالخيارات للتحقق من المستند.

```csharp
public abstract class VerifyOptions
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | قم بوضع علامة للتحقق من كل صفحة وثيقة. القيمة الافتراضية هي true. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | امتدادات إضافية للتحقق من خيارات التوقيع البديلة. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | علامة خاصية صالحة . |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | يجب التحقق من رقم صفحة المستند. إذا لم يتم تعيين الخاصية - سيتم التحقق من جميع صفحات المستند لأول مرة . الحد الأدنى للقيمة هو 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | خيارات الصفحة لتحديد الصفحات المراد التحقق منها . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
