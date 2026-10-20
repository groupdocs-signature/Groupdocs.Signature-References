---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Container voor QR-code-types."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Container voor QR-code-types.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec Barcode-type object. |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix Barcode-type object. |
|
|  | [QR](#QR) | QR Barcode-type object. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix Barcode Type object. |
|
|  | [GS1QR](#GS1QR) | GS1 QR Barcode Type object. |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code Type object. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code Type object. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code Type object. |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code Type object. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code Type object. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code Type object. |
|
|  | [HanXin](#HanXin) | Han Xin QR-Code Type object. |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code Type object. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Alle QRCode types. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Retourneert QRCode type met pasringType naam. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Retourneert QRCode type met pasringType naam. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Interne lijst van decodeertypen voor extractie |
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


Aztec Barcode-type object.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix Barcode-type object.


### QR {#QR}
```
public static final QrCodeType QR
```


QR Barcode-type object.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix Barcode Type object.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR Barcode Type object.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code Type object.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code Type object.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code Type object.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code Type object.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code Type object.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code Type object.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code Type object.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code Type object.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Alle QRCode types.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Retourneert QRCode type met pasringType naam. Als de naam van QRCode onbekend is - Exception wordt gegooid.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | parsingType | java.lang.String | Bronstring van QRCode type naam. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Retourneert QRCode type met pasringType naam.
Als de naam van QRCode onbekend is - geen Exception wordt gegooid, maar de methode retourneert een null-waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | parsingType | java.lang.String | Bronstring van QRCode type naam. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Interne lijst van decodeertypen voor extractie


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
