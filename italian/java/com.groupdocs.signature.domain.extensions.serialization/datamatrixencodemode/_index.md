---
title: "DataMatrixEncodeMode"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "La modalità di codifica degli encoder DataMatrix è impostata su Auto per impostazione predefinita"
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Modalità di codifica dell'encoder DataMatrix, predefinita su Auto

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Auto](#Auto) | Seleziona automaticamente la migliore modalità di codifica per la codifica DataMatrix |
|
|  | [ASCII](#ASCII) | Codifica un carattere alfanumerico o due caratteri numerici per byte |
|
|  | [Full](#Full) | Codifica valori a 8 bit |
|
|  | [Custom](#Custom) | Codifica con la codifica specificata in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Utilizza la codifica C40. |
|
|  | [Text](#Text) | Utilizza la codifica Text. |
|
|  | [EDIFACT](#EDIFACT) | Utilizza la codifica EDIFACT. |
|
|  | [ANSIX12](#ANSIX12) | Utilizza la codifica ANSI X12. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica nel code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Seleziona automaticamente la migliore modalità di codifica per la codifica DataMatrix


### ASCII {#ASCII}
```
public static final int ASCII
```


Codifica un carattere alfanumerico o due caratteri numerici per byte


### Full {#Full}
```
public static final int Full
```


Codifica valori a 8 bit


### Custom {#Custom}
```
public static final int Custom
```


Codifica con la codifica specificata in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding


### C40 {#C40}
```
public static final int C40
```


Utilizza la codifica C40. Codifica alfanumerici maiuscoli, minuscoli e caratteri speciali


### Text {#Text}
```
public static final int Text
```


Utilizza la codifica Text. Codifica alfanumerici minuscoli, maiuscoli e caratteri speciali.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Utilizza la codifica EDIFACT. Utilizza sei bit per carattere, codifica le cifre,
lettere maiuscole, e molte punteggiature, ma non supporta le lettere minuscole.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Utilizza la codifica ANSI X12.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica nel code-text.
Formato : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Gli schemi di codifica consentiti sono: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Esempio di code-text esteso: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
doppio\\edifact:EdifactEncodedText\"
Tutte le barre rovesciate (\\) devono essere raddoppiate nel testo.


