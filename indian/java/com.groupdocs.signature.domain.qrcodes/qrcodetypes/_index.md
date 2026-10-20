---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "QR कोड प्रकार कंटेनर।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

QR कोड प्रकार कंटेनर।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec बारकोड प्रकार ऑब्जेक्ट। |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix बारकोड प्रकार ऑब्जेक्ट। |
|
|  | [QR](#QR) | QR बारकोड प्रकार ऑब्जेक्ट। |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix बारकोड प्रकार ऑब्जेक्ट। |
|
|  | [GS1QR](#GS1QR) | GS1 QR बारकोड प्रकार ऑब्जेक्ट। |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [HanXin](#HanXin) | Han Xin QR-Code प्रकार ऑब्जेक्ट। |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code प्रकार ऑब्जेक्ट। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | सभी QRCode प्रकार। |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType नाम के साथ QRCode प्रकार लौटाता है। |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType नाम के साथ QRCode प्रकार लौटाता है। |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | निकालने के लिए डिकोड प्रकारों की आंतरिक सूची |
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


Aztec बारकोड प्रकार ऑब्जेक्ट।


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix बारकोड प्रकार ऑब्जेक्ट।


### QR {#QR}
```
public static final QrCodeType QR
```


QR बारकोड प्रकार ऑब्जेक्ट।


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix बारकोड प्रकार ऑब्जेक्ट।


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR बारकोड प्रकार ऑब्जेक्ट।


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code प्रकार ऑब्जेक्ट।


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code प्रकार ऑब्जेक्ट।


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code प्रकार ऑब्जेक्ट।


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code प्रकार ऑब्जेक्ट।


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code प्रकार ऑब्जेक्ट।


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code प्रकार ऑब्जेक्ट।


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code प्रकार ऑब्जेक्ट।


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code प्रकार ऑब्जेक्ट।


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


QR कोड प्रकार को pasringType नाम के साथ लौटाता है। यदि QR कोड का नाम अज्ञात है - Exception फेंका जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | parsingType | java.lang.String | QR कोड प्रकार नाम की स्रोत स्ट्रिंग। |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


pasringType नाम के साथ QRCode प्रकार लौटाता है।
यदि QR कोड का नाम अज्ञात है - कोई Exception नहीं फेंका जाएगा, बल्कि मेथड null मान लौटाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | parsingType | java.lang.String | QR कोड प्रकार नाम की स्रोत स्ट्रिंग। |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


निकालने के लिए डिकोड प्रकारों की आंतरिक सूची


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| प्रकार | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
