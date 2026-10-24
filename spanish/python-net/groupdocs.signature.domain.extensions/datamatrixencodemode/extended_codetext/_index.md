---
title: "Campo EXTENDED_CODETEXT"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación en code-text."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/extended_codetext/
is_root: false
weight: 3090
---


## EXTENDED_CODETEXT field

El modo ExtendedCodetext permite cambiar manualmente los esquemas de codificación en code-text. Formato: "\Encodation_scheme_name:text\Encodation_scheme_name:text". Los esquemas de codificación permitidos son: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Ejemplo de code-text extendido: @"\ansix12:ANSIX12TEXT\ascii:backslash must be \\ doubled\edifact:EdifactEncodedText" Todos los backslashes (\) deben duplicarse en el texto.

### Valor
`12`

### Ver también
* class [`DataMatrixEncodeMode`](/signature/python-net/groupdocs.signature.domain.extensions/datamatrixencodemode/)
