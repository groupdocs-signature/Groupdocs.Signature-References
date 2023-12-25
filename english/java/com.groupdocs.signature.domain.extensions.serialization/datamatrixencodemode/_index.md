---
title: DataMatrixEncodeMode
second_title: GroupDocs.Signature for Java API Reference
description: DataMatrix encoders encoding mode default to Auto
type: docs
weight: 13
url: /java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataMatrixEncodeMode extends System.Enum
```

DataMatrix encoder's encoding mode, default to Auto
## Fields

| Field | Description |
| --- | --- |
| [Auto](#Auto) | Automatically pick up the best encode mode for DataMatrix encoding |
| [ASCII](#ASCII) | Encodes one alphanumeric or two numeric characters per byte |
| [Full](#Full) | Encode 8 bit values |
| [Custom](#Custom) | Encode with the encoding specified in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| [C40](#C40) | Uses C40 encoding. |
| [Text](#Text) | Uses Text encoding. |
| [EDIFACT](#EDIFACT) | Uses EDIFACT encoding. |
| [ANSIX12](#ANSIX12) | Uses ANSI X12 encoding. |
| [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext mode allows to manually switch encoding schemes in code-text. |
### Auto {#Auto}
```
public static final int Auto
```


Automatically pick up the best encode mode for DataMatrix encoding

### ASCII {#ASCII}
```
public static final int ASCII
```


Encodes one alphanumeric or two numeric characters per byte

### Full {#Full}
```
public static final int Full
```


Encode 8 bit values

### Custom {#Custom}
```
public static final int Custom
```


Encode with the encoding specified in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding

### C40 {#C40}
```
public static final int C40
```


Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters

### Text {#Text}
```
public static final int Text
```


Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters.

### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters.

### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Uses ANSI X12 encoding.

### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext mode allows to manually switch encoding schemes in code-text. Format : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Allowed encoding schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Extended code-text example: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" All backslashes (\\) must be doubled in text.

