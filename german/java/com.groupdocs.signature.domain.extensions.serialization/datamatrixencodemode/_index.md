---
title: "DataMatrixEncodeMode"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "DataMatrix Encoder Kodierungsmodus standardmäßig auf Auto"
type: docs
weight: 13
url: /de/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Kodierungsmodus des DataMatrix-Encoders, standardmäßig auf Auto gesetzt

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Auto](#Auto) | Automatisch den besten Kodierungsmodus für DataMatrix‑Kodierung auswählen |
|
|  | [ASCII](#ASCII) | Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte |
|
|  | [Full](#Full) | 8‑Bit‑Werte kodieren |
|
|  | [Custom](#Custom) | Kodieren Sie mit der in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding angegebenen Kodierung |
|
|  | [C40](#C40) | Verwendet C40‑Kodierung. |
|
|  | [Text](#Text) | Verwendet Text‑Kodierung. |
|
|  | [EDIFACT](#EDIFACT) | Verwendet EDIFACT‑Kodierung. |
|
|  | [ANSIX12](#ANSIX12) | Verwendet ANSI X12‑Kodierung. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata im Code‑Text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Automatisch den besten Kodierungsmodus für DataMatrix‑Kodierung auswählen


### ASCII {#ASCII}
```
public static final int ASCII
```


Kodiert ein alphanumerisches oder zwei numerische Zeichen pro Byte


### Full {#Full}
```
public static final int Full
```


8‑Bit‑Werte kodieren


### Custom {#Custom}
```
public static final int Custom
```


Kodieren Sie mit der in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding angegebenen Kodierung


### C40 {#C40}
```
public static final int C40
```


Verwendet C40‑Kodierung. Kodiert Großbuchstaben‑alphanumerisch, Kleinbuchstaben und Sonderzeichen


### Text {#Text}
```
public static final int Text
```


Verwendet Text‑Kodierung. Kodiert Kleinbuchstaben‑alphanumerisch, Großbuchstaben und Sonderzeichen.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Verwendet EDIFACT‑Kodierung. Verwendet sechs Bits pro Zeichen, kodiert Ziffern,
Großbuchstaben und viele Satzzeichen, unterstützt jedoch keine Kleinbuchstaben.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Verwendet ANSI X12‑Kodierung.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


Der ExtendedCodetext‑Modus ermöglicht das manuelle Umschalten von Kodierungsschemata im Code‑Text.
Format: "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Zulässige Kodierungsschemata sind: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Beispiel für erweiterten Code‑Text: @"\\ansix12:ANSIX12TEXT\\ascii:Backslash muss \\\", "
verdoppelt\\edifact:EdifactEncodedText"
Alle Backslashes (\\) müssen im Text verdoppelt werden.


