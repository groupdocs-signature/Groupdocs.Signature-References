---
title: "Clase DataMatrixEncodeMode"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "DataMatrixEncodeMode enum — Referencia de la API .NET para Python de GroupDocs.Signature."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/
is_root: false
weight: 50
---


## DataMatrixEncodeMode class

El tipo DataMatrixEncodeMode expone los siguientes miembros:

### Campos
| Campo | Descripción |
| :- | :- |
| [AUTO](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/auto/) | Selecciona automáticamente el mejor modo de codificación para la codificación DataMatrix |
| [ASCII](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ascii/) | Codifica un carácter alfanumérico o dos caracteres numéricos por byte |
| [FULL](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/full/) | Codificar valores de 8 bits |
| [CUSTOM](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/custom/) | Codificar con la codificación especificada en BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/c40/) | Utiliza la codificación C40. Codifica alfanuméricos en mayúsculas, minúsculas y caracteres especiales |
| [TEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/text/) | Utiliza la codificación Text. Codifica alfanuméricos en minúsculas, mayúsculas y caracteres especiales. |
| [EDIFACT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/edifact/) | Utiliza la codificación EDIFACT. Usa seis bits por carácter, codifica dígitos, letras mayúsculas y muchos signos de puntuación, pero no admite letras minúsculas. |
| [ANSIX12](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/ansix12/) | Utiliza la codificación ANSI X12. |
| [EXTENDED_CODETEXT](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/) | El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación en code-text. Formato: "\Encodation_scheme_name:text\Encodation_scheme_name:text". Los esquemas de codificación permitidos son: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Ejemplo de code-text extendido: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Todos los backslashes (\) deben duplicarse en el texto. |

### Ver también
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
