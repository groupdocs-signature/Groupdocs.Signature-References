---
title: DataMatrixEncodeMode
second_title: GroupDocs.Signature لمرجع .NET API
description: وضع ترميز مشفر DataMatrix  افتراضيًا إلى Auto
type: docs
weight: 220
url: /ar/net/groupdocs.signature.domain.extensions/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

وضع ترميز مشفر DataMatrix ، افتراضيًا إلى Auto

```csharp
public enum DataMatrixEncodeMode
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| Auto | `0` | اختر تلقائيًا أفضل وضع تشفير لتشفير DataMatrix |
| ASCII | `1` | لتشفير حرف واحد أبجدي رقمي أو حرفين رقميين لكل بايت |
| Full | `6` | تشفير قيم 8 بت |
| Custom | `7` | التشفير باستخدام الترميز المحدد في BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | يستخدم تشفير C40. لتشفير الأحرف الأبجدية الرقمية الكبيرة والصغيرة والأحرف الخاصة |
| Text | `9` | يستخدم تشفير النص. لتشفير الأحرف الأبجدية الرقمية الصغيرة والحروف الكبيرة والأحرف الخاصة. |
| EDIFACT | `10` | يستخدم تشفير EDIFACT. يستخدم ستة بتات لكل حرف ، ويشفر الأرقام ، أحرف كبيرة ، والعديد من علامات الترقيم ، ولكن لا يدعم الأحرف الصغيرة. |
| ANSIX12 | `11` | يستخدم ترميز ANSI X12 . |
| ExtendedCodetext | `12` | يسمح وضع ExtendedCodetext بتبديل مخططات الترميز يدويًا في نص الكود. التنسيق: "\ Encodation_scheme_name: text \ Encodation_scheme_name: text" . مخططات التشفير المسموح بها هي: EDIFACT ، ANSIX12 ، ASCII ، C40 ، Text ، Ext. مثال نصي: @ "\ ansix12: ANSIX12TEXT \ ascii: يجب أن تكون الشرطة المائلة للخلف \\ double \ edifact: EdifactEncodedText" يجب مضاعفة جميع الخطوط المائلة العكسية (\) في النص. |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* المجسم [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
