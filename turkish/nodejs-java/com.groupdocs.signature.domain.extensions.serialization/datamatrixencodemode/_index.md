---
title: "DataMatrixEncodeMode"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "DataMatrix kodlayıcılarının kodlama modu varsayılan olarak Otomatik'tir."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

DataMatrix kodlayıcısının kodlama modu, varsayılan olarak Otomatik
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Auto](#Auto) | DataMatrix kodlaması için en iyi kodlama modunu otomatik olarak seç |
| [ASCII](#ASCII) | Her bayt için bir alfanümerik veya iki sayısal karakter kodlar |
| [Full](#Full) | 8 bit değerleri kodla |
| [Custom](#Custom) | BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding içinde belirtilen kodlamayla kodla |
| [C40](#C40) | C40 kodlamasını kullanır. |
| [Text](#Text) | Metin kodlamasını kullanır. |
| [EDIFACT](#EDIFACT) | EDIFACT kodlamasını kullanır. |
| [ANSIX12](#ANSIX12) | ANSI X12 kodlamasını kullanır. |
| [ExtendedCodetext](#ExtendedCodetext) | ExtendedCodetext modu, kod‑metninde kodlama şemalarını manuel olarak değiştirmeye izin verir. |
### Auto {#Auto}
```
public static final int Auto
```


DataMatrix kodlaması için en iyi kodlama modunu otomatik olarak seç

### ASCII {#ASCII}
```
public static final int ASCII
```


Her bayt için bir alfanümerik veya iki sayısal karakter kodlar

### Full {#Full}
```
public static final int Full
```


8 bit değerleri kodla

### Custom {#Custom}
```
public static final int Custom
```


BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding içinde belirtilen kodlamayla kodla

### C40 {#C40}
```
public static final int C40
```


C40 kodlamasını kullanır. Büyük harf alfanümerik, küçük harf ve özel karakterleri kodlar

### Text {#Text}
```
public static final int Text
```


Metin kodlamasını kullanır. Küçük harf alfanümerik, büyük harf ve özel karakterleri kodlar.

### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


EDIFACT kodlamasını kullanır. Karakter başına altı bit kullanır, rakamları, büyük harfleri ve birçok noktalama işaretini kodlar, ancak küçük harfleri desteklemez.

### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


ANSI X12 kodlamasını kullanır.

### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


ExtendedCodetext modu, kod‑metninde kodlama şemalarını manuel olarak değiştirmeye izin verir. Biçim : "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". İzin verilen kodlama şemaları şunlardır: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Uzatılmış kod‑metin örneği: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\\ doubled\\edifact:EdifactEncodedText" Tüm ters eğik çizgiler (\\) metinde iki kez olmalıdır.

