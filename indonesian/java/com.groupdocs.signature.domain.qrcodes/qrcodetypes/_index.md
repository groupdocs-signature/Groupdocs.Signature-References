---
title: "QrCodeTypes"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Kontainer Tipe QRCode."
type: docs
weight: 11
url: /id/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Kontainer Tipe QRCode.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Aztec](#Aztec) | Objek Tipe Barcode Aztec. |
|
|  | [DataMatrix](#DataMatrix) | Objek Tipe Barcode DataMatrix. |
|
|  | [QR](#QR) | Objek Tipe Barcode QR. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | Objek Tipe Barcode GS1 DataMatrix. |
|
|  | [GS1QR](#GS1QR) | Objek Tipe Barcode GS1 QR. |
|
|  | [HIBCLICQR](#HIBCLICQR) | Objek Tipe QR-Code HIBC LIC. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Objek Tipe QR-Code HIBC LIC Data Matrix. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | Objek Tipe QR-Code HIBC LIC Aztec. |
|
|  | [HIBCPASQR](#HIBCPASQR) | Objek Tipe QR-Code HIBC PAS. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Objek Tipe QR-Code HIBC PAS Data Matrix. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | Objek Tipe QR-Code HIBC PAS Aztec. |
|
|  | [HanXin](#HanXin) | Objek Tipe QR-Code Han Xin. |
|
|  | [GS1HanXin](#GS1HanXin) | Objek Tipe QR-Code GS1 Han Xin. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Semua tipe QRCode. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Mengembalikan tipe QRCode dengan nama pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Mengembalikan tipe QRCode dengan nama pasringType. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Daftar internal tipe Decode untuk ekstraksi |
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


Objek Tipe Barcode Aztec.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Objek Tipe Barcode DataMatrix.


### QR {#QR}
```
public static final QrCodeType QR
```


Objek Tipe Barcode QR.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Objek Tipe Barcode GS1 DataMatrix.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Objek Tipe Barcode GS1 QR.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Objek Tipe QR-Code HIBC LIC.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Objek Tipe QR-Code HIBC LIC Data Matrix.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Objek Tipe QR-Code HIBC LIC Aztec.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Objek Tipe QR-Code HIBC PAS.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Objek Tipe QR-Code HIBC PAS Data Matrix.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Objek Tipe QR-Code HIBC PAS Aztec.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Objek Tipe QR-Code Han Xin.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Objek Tipe QR-Code GS1 Han Xin.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Semua tipe QRCode.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Mengembalikan tipe QRCode dengan nama pasringType. Jika nama QRCode tidak diketahui - Exception akan dilempar


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | parsingType | java.lang.String | String sumber dari nama tipe QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Mengembalikan tipe QRCode dengan nama pasringType.
Jika nama QRCode tidak diketahui - tidak ada Exception yang akan dilempar tetapi metode akan mengembalikan nilai null.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | parsingType | java.lang.String | String sumber dari nama tipe QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Daftar internal tipe Decode untuk ekstraksi


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tipe | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
