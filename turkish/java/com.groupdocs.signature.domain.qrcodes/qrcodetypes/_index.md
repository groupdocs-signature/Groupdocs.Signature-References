---
title: "QrCodeTypes"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "QRCode Türleri konteyneri."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

QRCode Türleri konteyneri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec Barkod türü nesnesi. |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix Barkod türü nesnesi. |
|
|  | [QR](#QR) | QR Barkod türü nesnesi. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix Barkod türü nesnesi. |
|
|  | [GS1QR](#GS1QR) | GS1 QR Barkod türü nesnesi. |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code türü nesnesi. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code türü nesnesi. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code türü nesnesi. |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code türü nesnesi. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code türü nesnesi. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code Tür nesnesi. |
|
|  | [HanXin](#HanXin) | Han Xin QR-Code Tür nesnesi. |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code Tür nesnesi. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Tüm QRCode türleri. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | QRCode türünü pasringType adıyla döndürür. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | QRCode türünü pasringType adıyla döndürür. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Çıkarma için Decode Türlerinin iç listesi |
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


Aztec Barkod türü nesnesi.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix Barkod türü nesnesi.


### QR {#QR}
```
public static final QrCodeType QR
```


QR Barkod türü nesnesi.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix Barkod türü nesnesi.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR Barkod türü nesnesi.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code türü nesnesi.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code türü nesnesi.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code türü nesnesi.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code türü nesnesi.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code türü nesnesi.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code Tür nesnesi.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code Tür nesnesi.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code Tür nesnesi.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Tüm QRCode türleri.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


QRCode türünü pasringType adıyla döndürür. QRCode adı bilinmiyorsa - Exception fırlatılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | parsingType | java.lang.String | QRCode tür adı kaynağı dizesi. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


QRCode türünü pasringType adıyla döndürür.
QRCode adı bilinmiyorsa - Exception fırlatılmayacak ancak yöntem null değer döndürecektir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | parsingType | java.lang.String | QRCode tür adı kaynağı dizesi. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Çıkarma için Decode Türlerinin iç listesi


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
