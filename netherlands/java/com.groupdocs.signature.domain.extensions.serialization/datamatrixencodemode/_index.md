---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "De coderingsmodus van DataMatrix-encoders is standaard Auto"
type: docs
weight: 13
url: /nl/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Coderingsmodus van de DataMatrix‑encoder, standaard Auto.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Auto](#Auto) | Kies automatisch de beste coderingsmodus voor DataMatrix-codering |
|
|  | [ASCII](#ASCII) | Codeert één alfanumeriek of twee numerieke tekens per byte |
|
|  | [Full](#Full) | Codeer 8-bit waarden |
|
|  | [Custom](#Custom) | Codeer met de codering gespecificeerd in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Gebruikt C40-codering. |
|
|  | [Text](#Text) | Gebruikt tekstcodering. |
|
|  | [EDIFACT](#EDIFACT) | Gebruikt EDIFACT-codering. |
|
|  | [ANSIX12](#ANSIX12) | Gebruikt ANSI X12-codering. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext-modus maakt handmatig schakelen van coderingsschema's in code-tekst mogelijk. |
|
### Auto {#Auto}
```
public static final int Auto
```


Kies automatisch de beste coderingsmodus voor DataMatrix-codering


### ASCII {#ASCII}
```
public static final int ASCII
```


Codeert één alfanumeriek of twee numerieke tekens per byte


### Full {#Full}
```
public static final int Full
```


Codeer 8-bit waarden


### Custom {#Custom}
```
public static final int Custom
```


Codeer met de codering gespecificeerd in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding


### C40 {#C40}
```
public static final int C40
```


Gebruikt C40-codering. Codeert hoofdletter alfanumeriek, kleine letters en speciale tekens


### Text {#Text}
```
public static final int Text
```


Gebruikt tekstcodering. Codeert kleine letters alfanumeriek, hoofdletters en speciale tekens.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, codeert cijfers,
hoofdletters, en veel interpunctietekens, maar ondersteunt geen kleine letters.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Gebruikt ANSI X12-codering.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext-modus maakt handmatig schakelen van coderingsschema's in code-tekst mogelijk.
Formaat : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Toegestane coderingsschema's zijn: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Uitgebreid code-tekst voorbeeld: @\"\\ansix12:ANSIX12TEXT\\ascii:backslash moet \\\\"
verdubbeld\\edifact:EdifactEncodedText\"
Alle backslashes (\\) moeten in de tekst worden verdubbeld.


