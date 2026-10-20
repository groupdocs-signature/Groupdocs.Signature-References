---
title: "DataMatrixEncodeMode"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mode enkoding pengkode DataMatrix default ke Auto"
type: docs
weight: 13
url: /id/java/com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object
```
public final class DataMatrixEncodeMode
```

Mode pengkodean enkoder DataMatrix, default ke Auto.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Auto](#Auto) | Secara otomatis memilih mode enkode terbaik untuk enkoding DataMatrix |
|
|  | [ASCII](#ASCII) | Mengenkripsi satu karakter alfanumerik atau dua karakter numerik per byte |
|
|  | [Full](#Full) | Enkode nilai 8 bit |
|
|  | [Custom](#Custom) | Enkode dengan enkoding yang ditentukan dalam BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
|
|  | [C40](#C40) | Menggunakan enkoding C40. |
|
|  | [Text](#Text) | Menggunakan enkoding Text. |
|
|  | [EDIFACT](#EDIFACT) | Menggunakan enkoding EDIFACT. |
|
|  | [ANSIX12](#ANSIX12) | Menggunakan enkoding ANSI X12. |
|
|  | [ExtendedCodetext](#ExtendedCodetext) | Mode ExtendedCodetext memungkinkan untuk secara manual mengganti skema enkoding dalam code-text. |
|
### Auto {#Auto}
```
public static final int Auto
```


Secara otomatis memilih mode enkode terbaik untuk enkoding DataMatrix


### ASCII {#ASCII}
```
public static final int ASCII
```


Mengenkripsi satu karakter alfanumerik atau dua karakter numerik per byte


### Full {#Full}
```
public static final int Full
```


Enkode nilai 8 bit


### Custom {#Custom}
```
public static final int Custom
```


Enkode dengan enkoding yang ditentukan dalam BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding


### C40 {#C40}
```
public static final int C40
```


Menggunakan enkoding C40. Mengenkripsi alfanumerik huruf besar, huruf kecil, dan karakter khusus


### Text {#Text}
```
public static final int Text
```


Menggunakan enkoding Text. Mengenkripsi alfanumerik huruf kecil, huruf besar, dan karakter khusus.


### EDIFACT {#EDIFACT}
```
public static final int EDIFACT
```


Menggunakan enkoding EDIFACT. Menggunakan enam bit per karakter, mengenkripsi digit,
huruf besar, dan banyak tanda baca, tetapi tidak mendukung huruf kecil.


### ANSIX12 {#ANSIX12}
```
public static final int ANSIX12
```


Menggunakan enkoding ANSI X12.


### ExtendedCodetext {#ExtendedCodetext}
```
public static final int ExtendedCodetext
```


Mode ExtendedCodetext memungkinkan untuk secara manual mengganti skema enkoding dalam code-text.
Format : "\\Encodation_scheme_name:text\\Encodation_scheme_name:text".
Skema enkoding yang diizinkan adalah: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.
Contoh code-text Extended: @"\\ansix12:ANSIX12TEXT\\ascii:backslash must be \\\",
digandakan\\edifact:EdifactEncodedText"
Semua backslash (\\) harus digandakan dalam teks.


