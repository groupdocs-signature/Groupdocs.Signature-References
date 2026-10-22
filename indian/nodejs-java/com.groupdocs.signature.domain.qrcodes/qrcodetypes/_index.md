---
title: "QrCodeTypes"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "क्यूआरकोड प्रकार कंटेनर।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

क्यूआरकोड प्रकार कंटेनर।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Aztec](#Aztec) | Aztec बारकोड प्रकार वस्तु। |
| [DataMatrix](#DataMatrix) | DataMatrix बारकोड प्रकार वस्तु। |
| [QR](#QR) | QR बारकोड प्रकार वस्तु। |
| [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix बारकोड प्रकार वस्तु। |
| [GS1QR](#GS1QR) | GS1 QR बारकोड प्रकार वस्तु। |
| [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code प्रकार वस्तु। |
| [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code प्रकार वस्तु। |
| [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code प्रकार वस्तु। |
| [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code प्रकार वस्तु। |
| [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code प्रकार वस्तु। |
| [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code प्रकार वस्तु। |
| [HanXin](#HanXin) | Han Xin QR-Code प्रकार वस्तु। |
| [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code प्रकार वस्तु। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | सभी QRCode प्रकार। |
| [parse(String parsingType)](#parse-java.lang.String-) | pasringType नाम के साथ QRCode प्रकार लौटाता है। |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType नाम के साथ QRCode प्रकार लौटाता है। |
| [getDecodeTypes()](#getDecodeTypes--) | निकालने के लिए डिकोड प्रकारों की आंतरिक सूची। |
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


Aztec बारकोड प्रकार वस्तु।

### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix बारकोड प्रकार वस्तु।

### QR {#QR}
```
public static final QrCodeType QR
```


QR बारकोड प्रकार वस्तु।

### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix बारकोड प्रकार वस्तु।

### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR बारकोड प्रकार वस्तु।

### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code प्रकार वस्तु।

### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code प्रकार वस्तु।

### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code प्रकार वस्तु।

### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code प्रकार वस्तु।

### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code प्रकार वस्तु।

### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code प्रकार वस्तु।

### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code प्रकार वस्तु।

### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code प्रकार वस्तु।

### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


सभी QRCode प्रकार।

**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


pasringType नाम के साथ QRCode प्रकार लौटाता है। यदि QRCode का नाम अज्ञात है - Exception फेंका जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | QRCode प्रकार नाम की स्रोत स्ट्रिंग। |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


pasringType नाम के साथ QRCode प्रकार लौटाता है। यदि QRCode का नाम अज्ञात है - कोई Exception नहीं फेंका जाएगा बल्कि विधि null मान लौटाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | QRCode प्रकार नाम की स्रोत स्ट्रिंग। |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


निकालने के लिए डिकोड प्रकारों की आंतरिक सूची।

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रकार | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
