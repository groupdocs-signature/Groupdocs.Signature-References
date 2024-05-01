---
title: QrCodeTypes
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: QRCode Types container.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

QRCode Types container.
## Constructors

| Constructor | Description |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Fields

| Field | Description |
| --- | --- |
| [Aztec](#Aztec) | Aztec Barcode Type object. |
| [DataMatrix](#DataMatrix) | DataMatrix Barcode Type object. |
| [QR](#QR) | QR Barcode Type object. |
| [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix Barcode Type object. |
| [GS1QR](#GS1QR) | GS1 QR Barcode Type object. |
| [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code Type object. |
| [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code Type object. |
| [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code Type object. |
| [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code Type object. |
| [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code Type object. |
| [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code Type object. |
| [HanXin](#HanXin) | Han Xin QR-Code Type object. |
| [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code Type object. |
## Methods

| Method | Description |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | All QRCode types. |
| [parse(String parsingType)](#parse-java.lang.String-) | Returns QRCode type with pasringType name. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Returns QRCode type with pasringType name. |
| [getDecodeTypes()](#getDecodeTypes--) | Internal list of Decode Types for extraction |
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


Aztec Barcode Type object.

### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix Barcode Type object.

### QR {#QR}
```
public static final QrCodeType QR
```


QR Barcode Type object.

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


All QRCode types.

**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Returns QRCode type with pasringType name. If name of QRCode is unknown - Exception will be throw

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Source string of QRCode type name. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Returns QRCode type with pasringType name. If name of QRCode is unknown - no Exception will be throw but method will return null value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Source string of QRCode type name. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Internal list of Decode Types for extraction

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| type | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
