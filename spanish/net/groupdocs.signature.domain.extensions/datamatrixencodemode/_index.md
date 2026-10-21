---
title: "DataMatrixEncodeMode"
second_title: "Referencia de la API de GroupDocs.Signature para .NET"
description: "El modo de codificación de los codificadores DataMatrix por defecto es Auto"
type: docs
weight: 230
url: /es/net/groupdocs.signature.domain.extensions/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Modo de codificación del codificador DataMatrix, por defecto Auto

```csharp
public enum DataMatrixEncodeMode
```

### Values

| Nombre | Value | Descripción |
| --- | --- | --- |
| Auto | `0` | Selecciona automáticamente el mejor modo de codificación para la codificación DataMatrix |
| ASCII | `1` | Codifica un carácter alfanumérico o dos caracteres numéricos por byte |
| Full | `6` | Codifica valores de 8 bits |
| Custom | `7` | Codifica con la codificación especificada en BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | Utiliza la codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales |
| Text | `9` | Utiliza la codificación Text. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales. |
| EDIFACT | `10` | Utiliza la codificación EDIFACT. Usa seis bits por carácter, codifica dígitos, letras mayúsculas y muchos signos de puntuación, pero no admite letras minúsculas. |
| ANSIX12 | `11` | Utiliza la codificación ANSI X12. |
| ExtendedCodetext | `12` | El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación en el código de texto. Formato: "\Encodation_scheme_name:text\Encodation_scheme_name:text". Los esquemas de codificación permitidos son: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Ejemplo de código de texto extendido: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Todas las barras invertidas (\\) deben duplicarse en el texto. |

### Ver también

* namespace [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* assembly [GroupDocs.Signature](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.signature.dll -->
