---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature för Java API-referens"
description: "DataMatrix kodares kodningsläge är som standard Auto"
type: docs
weight: 13
url: /sv/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

DataMatrix-kodarens kodningsläge, standard är Auto.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Auto](#Auto) | Välj automatiskt det bästa kodningsläget för DataMatrix-kodning |
|
|  | [ASCII](#ASCII) | Kodar en alfanumerisk eller två numeriska tecken per byte |
|
|  | [Full](#Full) | Koda 8-bitarsvärden |
|
|  | [Custom](#Custom) | Koda med den kodning som anges i BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Använder C40-kodning. |
|
|  | [Text](#Text) | Använder Text-kodning. |
|
|  | [EDIFACT](#EDIFACT) | Använder EDIFACT-kodning. |
|
|  | [ANSIX12](#ANSIX12) | Använder ANSI X12-kodning. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext-läget tillåter att manuellt växla kodningsscheman i code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Välj automatiskt det bästa kodningsläget för DataMatrix-kodning


### ASCII {#ASCII}
```
public static final int ASCII
```


Kodar en alfanumerisk eller två numeriska tecken per byte


### Full {#Full}
```
public static final int Full
```


Koda 8-bitarsvärden


### Custom {#Custom}
```
public static final int Custom
```


Koda med den kodning som anges i BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding


### C40 {#C40}
```
public static final int C40
```


Använder C40-kodning. Kodar versala alfanumeriska, gemena och specialtecken


### Text {#Text}
```
public static final int Text
```


Använder Text-kodning. Kodar gemena alfanumeriska, versala och specialtecken.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Använder EDIFACT-kodning. Använder sex bitar per tecken, kodar siffror,
versala bokstäver, och många skiljetecken, men har inget stöd för gemena bokstäver.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Använder ANSI X12-kodning.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext-läget tillåter att manuellt växla kodningsscheman i code-text.
Format: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Tillåtna kodningsscheman är: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Exempel på utökad code-text: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
dubblerad\\edifact:EdifactEncodedText"
Alla bakåtsnedstreck (\\) måste dubbleras i text.


