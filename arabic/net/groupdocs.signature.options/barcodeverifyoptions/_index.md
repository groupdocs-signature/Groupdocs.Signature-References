---
title: BarcodeVerifyOptions
second_title: GroupDocs.Signature لمرجع .NET API
description: يمثل خيارات التحقق من الرمز الشريطي.
type: docs
weight: 1270
url: /ar/net/groupdocs.signature.options/barcodeverifyoptions/
---
## BarcodeVerifyOptions class

يمثل خيارات التحقق من الرمز الشريطي.

```csharp
public class BarcodeVerifyOptions : TextVerifyOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor)() | إنشاء خيار التحقق الافتراضي لتوقيع الرمز الشريطي . |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_1)(BarcodeType) | إنشاء خيار التحقق الافتراضي باستخدام التحقق من نوع الرمز الشريطي |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_2)(string) | إنشاء خيار التحقق الافتراضي مع نص التحقق |
| [BarcodeVerifyOptions](barcodeverifyoptions#constructor_3)(string, BarcodeType) | إنشاء خيار التحقق الافتراضي مع التحقق من نوع الرمز الشريطي والنص |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | قم بوضع علامة للتحقق من كل صفحة وثيقة. القيمة الافتراضية هي true. |
| [EncodeType](../../groupdocs.signature.options/barcodeverifyoptions/encodetype) { get; set; } | الحصول على التحقق من نوع الرمز الشريطي أو تعيينه. |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | امتدادات إضافية للتحقق من خيارات التوقيع البديلة. |
| [FormTextFieldTitle](../../groupdocs.signature.options/textverifyoptions/formtextfieldtitle) { get; set; } | الحصول على عنوان حقل النموذج أو تعيينه للتحقق منه. إذا كان سيتم العثور على نص مجموعة الخاصية هذه فقط في حقول النموذج النصي. |
| [FormTextFieldType](../../groupdocs.signature.options/textverifyoptions/formtextfieldtype) { get; set; } | الحصول على نوع حقل النموذج أو تعيينه للتحقق منه. إذا كان سيتم العثور على نص مجموعة الخاصية هذه فقط في حقول النموذج النصي. |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | علامة خاصية صالحة . |
| [MatchType](../../groupdocs.signature.options/textverifyoptions/matchtype) { get; set; } | الحصول على التحقق من نوع مطابقة النص أو تعيينه. |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | يجب التحقق من رقم صفحة المستند. إذا لم يتم تعيين الخاصية - سيتم التحقق من جميع صفحات المستند لأول مرة . الحد الأدنى للقيمة هو 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | خيارات الصفحة لتحديد الصفحات المراد التحقق منها . |
| [SignatureID](../../groupdocs.signature.options/textverifyoptions/signatureid) { get; set; } | حدد معرف توقيع النص أكثر من الصفر إذا كان يجب التحقق منه. هذه الخاصية مدعومة فقط لمستندات Pdf |
| [SignatureImplementation](../../groupdocs.signature.options/textverifyoptions/signatureimplementation) { get; set; } | نوع التوقيع المراد التحقق منه . |
| [Text](../../groupdocs.signature.options/textverifyoptions/text) { get; set; } | حدد نص التوقيع إذا كان يجب التحقق منه . |

### ملاحظات

**يتعلم أكثر**

* الاستخدام الأساسي للتحقق من التوقيع الإلكتروني للرمز الشريطي بواسطة GroupDocs. التوقيع: [ كيفية التحقق من صحة توقيعات الباركود في مستند](https://docs.groupdocs.com/display/signaturenet/Verify+Barcode+signatures+in+the+document)
* الاستخدام المتقدم لإعدادات التحقق للتوقيع الإلكتروني للرمز الشريطي مع GroupDocs. التوقيع: [الاستخدام المتقدم لتواقيع eVerification Barcode في مستند وإعدادات إضافية]()

### أنظر أيضا

* class [TextVerifyOptions](../textverifyoptions)
* مساحة الاسم [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
