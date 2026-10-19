---
title: "DataMatrixEncodeMode"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "وضع ترميز مشفرات DataMatrix الافتراضي إلى Auto"
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

وضع الترميز لمشفّر DataMatrix، الافتراضي هو تلقائي.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Auto](#Auto) | اختيار الوضع الأفضل للترميز تلقائيًا لتشفير DataMatrix |
|
|  | [ASCII](#ASCII) | يقوم بترميز حرف أبجدي رقمي واحد أو حرفين رقميين لكل بايت |
|
|  | [Full](#Full) | ترميز قيم 8 بت |
|
|  | [Custom](#Custom) | ترميز باستخدام الترميز المحدد في BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | يستخدم ترميز C40. |
|
|  | [Text](#Text) | يستخدم ترميز Text. |
|
|  | [EDIFACT](#EDIFACT) | يستخدم ترميز EDIFACT. |
|
|  | [ANSIX12](#ANSIX12) | يستخدم ترميز ANSI X12. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | وضع ExtendedCodetext يسمح بالتبديل اليدوي لخطط الترميز في code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


اختيار الوضع الأفضل للترميز تلقائيًا لتشفير DataMatrix


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


يستخدم ترميز Text. يرمز إلى الأحرف الأبجدية الرقمية الصغيرة، الأحرف الكبيرة والرموز الخاصة.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


يستخدم ترميز EDIFACT. يستخدم ستة بتات لكل حرف، يرمز إلى الأرقام،
الأحرف الكبيرة، والعديد من علامات الترقيم، لكنه لا يدعم الأحرف الصغيرة.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


يستخدم ترميز ANSI X12.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


وضع ExtendedCodetext يسمح بالتبديل اليدوي لخطط الترميز في code-text.
الصيغة : "\\\\Encodation_scheme_name:text\\\\Encodation_scheme_name:text".
خطط الترميز المسموح بها هي: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
مثال على code-text الموسع: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
مضاعف\\edifact:EdifactEncodedText\"
يجب مضاعفة جميع الشرط المائلة العكسية (\\\\) في النص.


