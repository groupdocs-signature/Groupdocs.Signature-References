---
title: QrCodeTypes
second_title: GroupDocs.Signature for Java API Reference
description: QRCode Types container.
type: docs
weight: 11
url: /java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
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
## Methods

| Method | Description |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | All QRCode types. |
| [parse(String parsingType)](#parse-java.lang.String-) | Returns QRCode type with pasringType name. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Returns QRCode type with pasringType name. |
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
