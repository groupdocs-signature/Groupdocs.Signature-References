---
title: "DataMatrixEncodeMode"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "El modo de codificación de los codificadores DataMatrix es Auto por defecto"
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Modo de codificación del codificador DataMatrix, por defecto Auto.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Auto](#Auto) | Selecciona automáticamente el mejor modo de codificación para la codificación DataMatrix |
|
|  | [ASCII](#ASCII) | Codifica un carácter alfanumérico o dos caracteres numéricos por byte |
|
|  | [Full](#Full) | Codificar valores de 8 bits |
|
|  | [Custom](#Custom) | Codificar con la codificación especificada en BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Utiliza codificación C40. |
|
|  | [Text](#Text) | Utiliza codificación Text. |
|
|  | [EDIFACT](#EDIFACT) | Utiliza codificación EDIFACT. |
|
|  | [ANSIX12](#ANSIX12) | Utiliza codificación ANSI X12. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación en code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Selecciona automáticamente el mejor modo de codificación para la codificación DataMatrix


### ASCII {#ASCII}
```
public static final int ASCII
```


Codifica un carácter alfanumérico o dos caracteres numéricos por byte


### Full {#Full}
```
public static final int Full
```


Codificar valores de 8 bits


### Custom {#Custom}
```
public static final int Custom
```


Codificar con la codificación especificada en BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding


### C40 {#C40}
```
public static final int C40
```


Utiliza codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales


### Text {#Text}
```
public static final int Text
```


Utiliza codificación Text. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Utiliza codificación EDIFACT. Usa seis bits por carácter, codifica dígitos,
letras mayúsculas, y muchos signos de puntuación, pero no tiene soporte para letras minúsculas.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Utiliza codificación ANSI X12.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación en code-text.
Formato : \"\\Encodation_scheme_name:text\\Encodation_scheme_name:text\".
Los esquemas de codificación permitidos son: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Ejemplo de code-text extendido: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\\",
duplicado\\edifact:EdifactEncodedText\"
Todas las barras invertidas (\\\\) deben duplicarse en el texto.


