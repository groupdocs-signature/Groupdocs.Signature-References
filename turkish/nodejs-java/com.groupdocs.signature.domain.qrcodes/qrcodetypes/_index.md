---
title: "QrCodeTypes"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "QRCode Türleri konteyneri."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
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
| [Aztec](#Aztec) | Aztec Barkod Türü nesnesi. |
| [DataMatrix](#DataMatrix) | DataMatrix Barkod Türü nesnesi. |
| [QR](#QR) | QR Barkod Türü nesnesi. |
| [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix Barkod Türü nesnesi. |
| [GS1QR](#GS1QR) | GS1 QR Barkod Türü nesnesi. |
| [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code Türü nesnesi. |
| [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code Türü nesnesi. |
| [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code Türü nesnesi. |
| [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code Türü nesnesi. |
| [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code Türü nesnesi. |
| [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code Türü nesnesi. |
| [HanXin](#HanXin) | Han Xin QR-Code Türü nesnesi. |
| [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code Türü nesnesi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Tüm QRCode türleri. |
| [parse(String parsingType)](#parse-java.lang.String-) | pasringType adıyla QRCode türünü döndürür. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType adıyla QRCode türünü döndürür. |
| [getDecodeTypes()](#getDecodeTypes--) | Çıkarma için Decode Türlerinin iç listesi |
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


Aztec Barkod Türü nesnesi.

### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix Barkod Türü nesnesi.

### QR {#QR}
```
public static final QrCodeType QR
```


QR Barkod Türü nesnesi.

### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix Barkod Türü nesnesi.

### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR Barkod Türü nesnesi.

### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code Türü nesnesi.

### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code Türü nesnesi.

### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code Türü nesnesi.

### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code Türü nesnesi.

### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code Türü nesnesi.

### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code Türü nesnesi.

### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code Türü nesnesi.

### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code Türü nesnesi.

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


pasringType adıyla QRCode türünü döndürür. QRCode adı bilinmiyorsa - Exception fırlatılacak

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | QRCode türü adının kaynak dizesi. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


pasringType adıyla QRCode türünü döndürür. QRCode adı bilinmiyorsa - Exception fırlatılmayacak, ancak yöntem null değer döndürecek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | java.lang.String | QRCode türü adının kaynak dizesi. |

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
