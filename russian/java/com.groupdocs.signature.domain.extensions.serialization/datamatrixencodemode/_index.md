---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Режим кодирования кодировщиков DataMatrix по умолчанию Auto"
type: docs
weight: 13
url: /ru/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Режим кодирования кодировщика DataMatrix, по умолчанию Auto.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Auto](#Auto) | Автоматически подбирать лучший режим кодирования для DataMatrix |
|
|  | [ASCII](#ASCII) | Кодирует один буквенно-цифровой или два числовых символа на байт |
|
|  | [Full](#Full) | Кодировать 8‑битные значения |
|
|  | [Custom](#Custom) | Кодировать с использованием кодировки, указанной в BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Использует кодировку C40. |
|
|  | [Text](#Text) | Использует кодировку Text. |
|
|  | [EDIFACT](#EDIFACT) | Использует кодировку EDIFACT. |
|
|  | [ANSIX12](#ANSIX12) | Использует кодировку ANSI X12. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | Режим ExtendedCodetext позволяет вручную переключать схемы кодирования в code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Автоматически подбирать лучший режим кодирования для DataMatrix


### ASCII {#ASCII}
```
public static final int ASCII
```


Кодирует один буквенно-цифровой или два числовых символа на байт


### Full {#Full}
```
public static final int Full
```


Кодировать 8‑битные значения


### Custom {#Custom}
```
public static final int Custom
```


Кодировать с использованием кодировки, указанной в BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding


### C40 {#C40}
```
public static final int C40
```


Использует кодировку C40. Кодирует заглавные буквенно-цифровые, строчные и специальные символы


### Text {#Text}
```
public static final int Text
```


Использует кодировку Text. Кодирует строчные буквенно-цифровые, заглавные и специальные символы.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Использует кодировку EDIFACT. Использует шесть бит на символ, кодирует цифры,
заглавные буквы и множество знаков пунктуации, но не поддерживает строчные буквы.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Использует кодировку ANSI X12.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


Режим ExtendedCodetext позволяет вручную переключать схемы кодирования в code-text.
Формат : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Допустимые схемы кодирования: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Пример расширенного code-text: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
удвоенный\\edifact:EdifactEncodedText"
Все обратные слеши (\\) должны быть удвоены в тексте.


