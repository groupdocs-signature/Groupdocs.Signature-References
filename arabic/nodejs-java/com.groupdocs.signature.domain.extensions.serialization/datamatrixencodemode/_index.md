---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "وضع ترميز مشفرات DataMatrix الافتراضي هو Auto"
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

وضع الترميز لمشفّر DataMatrix، الافتراضي هو تلقائي
## الحقول

| حقل | الوصف |
| --- | --- |
| [Auto](#Auto) | التقاط تلقائيًا أفضل وضع ترميز لتشفير DataMatrix |
| [ASCII](#ASCII) | يقوم بترميز حرف أبجدي رقمي واحد أو حرفين رقميين لكل بايت |
| [Full](#Full) | ترميز قيم 8 بت |
| [Custom](#Custom) | ترميز باستخدام الترميز المحدد في BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](#C40) | يستخدم ترميز C40. |
| [Text](#Text) | يستخدم ترميز النص. |
| [EDIFACT](#EDIFACT) | يستخدم ترميز EDIFACT. |
| [ANSIX12](#ANSIX12) | يستخدم ترميز ANSI X12. |
| [ExtendedCodetext](#ExtendedCodetext) | وضع ExtendedCodetext يسمح بالتبديل اليدوي بين مخططات الترميز في code-text. |
### Auto {#Auto}
```
public static final int Auto
```


التقاط تلقائيًا أفضل وضع ترميز لتشفير DataMatrix

### ASCII {#ASCII}
```
public static final int ASCII
```


يقوم بترميز حرف أبجدي رقمي واحد أو حرفين رقميين لكل بايت

### Full {#Full}
```
public static final int Full
```


ترميز قيم 8 بت

### Custom {#Custom}
```
public static final int Custom
```


ترميز باستخدام الترميز المحدد في BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding

### C40 {#C40}
```
public static final int C40
```


يستخدم ترميز C40. يرمز إلى الأحرف الأبجدية الرقمية الكبيرة، الأحرف الصغيرة والرموز الخاصة

### Text {#Text}
```
public static final int Text
```


يستخدم ترميز النص. يرمز إلى الأحرف الأبجدية الرقمية الصغيرة، الأحرف الكبيرة والرموز الخاصة.

### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


يستخدم ترميز EDIFACT. يستخدم ست بتات لكل حرف، يرمز إلى الأرقام، الأحرف الكبيرة، والعديد من علامات الترقيم، لكنه لا يدعم الأحرف الصغيرة.

### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


يستخدم ترميز ANSI X12.

### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


وضع ExtendedCodetext يسمح بالتبديل اليدوي بين مخططات الترميز في code-text. الصيغة : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". مخططات الترميز المسموح بها هي: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. مثال على code-text الموسع: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" يجب أن تكون جميع الشرطات المائلة (\\) مضاعفة في النص.

