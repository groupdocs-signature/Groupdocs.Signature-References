---
title: QrCodeTypes
second_title: GroupDocs.Signature لمرجع .NET API
description: حاوية أنواع كود QRC.
type: docs
weight: 780
url: /ar/net/groupdocs.signature.domain/qrcodetypes/
---
## QrCodeTypes class

حاوية أنواع كود QRC.

```csharp
public static class QrCodeTypes
```

## الخصائص

| اسم | وصف |
| --- | --- |
| static [AllTypes](../../groupdocs.signature.domain/qrcodetypes/alltypes) { get; } | جميع أنواع كود QRC. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Parse](../../groupdocs.signature.domain/qrcodetypes/parse)(string) | إرجاع نوع رمز QRC مع اسم النوع السرّي. إذا كان اسم رمز الاستجابة السريعة غير معروف - فسيتم طرح الاستثناء |
| static [TryParse](../../groupdocs.signature.domain/qrcodetypes/tryparse)(string) | إرجاع نوع رمز QRC مع اسم النوع السرّي. إذا كان اسم رمز QRCode غير معروف - لن يتم طرح أي استثناء ولكن الطريقة ستعيد قيمة فارغة. |

## مجالات

| اسم | وصف |
| --- | --- |
| static readonly [Aztec](../../groupdocs.signature.domain/qrcodetypes/aztec) | كائن نوع رمز QR- رمز Aztec . |
| static readonly [DataMatrix](../../groupdocs.signature.domain/qrcodetypes/datamatrix) | كائن نوع رمز الاستجابة السريعة DataMatrix . |
| static readonly [GS1DataMatrix](../../groupdocs.signature.domain/qrcodetypes/gs1datamatrix) | GS1 DataMatrix QR-Code Type object. |
| static readonly [GS1QR](../../groupdocs.signature.domain/qrcodetypes/gs1qr) | GS1 QR-Code Type object. |
| static readonly [QR](../../groupdocs.signature.domain/qrcodetypes/qr) | QR-Code نوع كائن . |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->