---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Container för QRCode-typer."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Container för QRCode-typer.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec streckkodstyp objekt. |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix streckkodstyp objekt. |
|
|  | [QR](#QR) | QR streckkodstyp objekt. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix streckkodstyp objekt. |
|
|  | [GS1QR](#GS1QR) | GS1 QR streckkodstyp objekt. |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-kodstyp objekt. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-kodstyp objekt. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-kodstyp objekt. |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-kodstyp objekt. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-kodstyp objekt. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-kodstyp objekt. |
|
|  | [HanXin](#HanXin) | Han Xin QR-kodstyp objekt. |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-kodstyp objekt. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Alla QRCode-typer. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Returnerar QRCode-typ med pasringType-namn. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Returnerar QRCode-typ med pasringType-namn. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Intern lista över avkodningstyper för extraktion |
|
| [isComplexType(System.Type type, QrCodeType qrCodeType)](#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-) |  |
| [getDataEncoding(System.Type type, QrCodeType qrCodeType)](#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-) |  |
### QrCodeTypes() {#QrCodeTypes--}
```
public QrCodeTypes()
```


### Aztec {#Aztec}
```
public static final QrCodeType Aztec
```


Aztec streckkodstyp objekt.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix streckkodstyp objekt.


### QR {#QR}
```
public static final QrCodeType QR
```


QR streckkodstyp objekt.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix streckkodstyp objekt.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR streckkodstyp objekt.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-kodstyp objekt.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-kodstyp objekt.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-kodstyp objekt.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-kodstyp objekt.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-kodstyp objekt.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-kodstyp objekt.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-kodstyp objekt.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-kodstyp objekt.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Alla QRCode-typer.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Returnerar QRCode-typ med pasringType-namn. Om namnet på QRCode är okänt - Exception kommer att kastas


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | parsingType | java.lang.String | Källsträng för QRCode-typnamn. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Returnerar QRCode-typ med pasringType-namn.
Om namnet på QRCode är okänt - ingen Exception kommer att kastas men metoden returnerar nullvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | parsingType | java.lang.String | Källsträng för QRCode-typnamn. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Intern lista över avkodningstyper för extraktion


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
