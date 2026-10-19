---
title: "QrCodeTypes"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Κοντέινερ τύπων QRCode."
type: docs
weight: 11
url: /el/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Κοντέινερ τύπων QRCode.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Aztec](#Aztec) | Αντικείμενο τύπου Aztec Barcode. |
|
|  | [DataMatrix](#DataMatrix) | Αντικείμενο τύπου DataMatrix Barcode. |
|
|  | [QR](#QR) | Αντικείμενο τύπου QR Barcode. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | Αντικείμενο τύπου GS1 DataMatrix Barcode. |
|
|  | [GS1QR](#GS1QR) | Αντικείμενο τύπου GS1 QR Barcode. |
|
|  | [HIBCLICQR](#HIBCLICQR) | Αντικείμενο τύπου HIBC LIC QR-Code. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Αντικείμενο τύπου HIBC LIC Data Matrix QR-Code. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | Αντικείμενο τύπου HIBC LIC Aztec QR-Code. |
|
|  | [HIBCPASQR](#HIBCPASQR) | Αντικείμενο τύπου HIBC PAS QR-Code. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Αντικείμενο τύπου HIBC PAS Data Matrix QR-Code. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | Αντικείμενο τύπου HIBC PAS Aztec QR-Code. |
|
|  | [HanXin](#HanXin) | Αντικείμενο τύπου Han Xin QR-Code. |
|
|  | [GS1HanXin](#GS1HanXin) | Αντικείμενο τύπου GS1 Han Xin QR-Code. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Όλοι οι τύποι QRCode. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Επιστρέφει τύπο QRCode με το όνομα pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Επιστρέφει τύπο QRCode με το όνομα pasringType. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Εσωτερική λίστα τύπων Decode για εξαγωγή. |
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


Αντικείμενο τύπου Aztec Barcode.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Αντικείμενο τύπου DataMatrix Barcode.


### QR {#QR}
```
public static final QrCodeType QR
```


Αντικείμενο τύπου QR Barcode.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Αντικείμενο τύπου GS1 DataMatrix Barcode.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Αντικείμενο τύπου GS1 QR Barcode.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Αντικείμενο τύπου HIBC LIC QR-Code.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Αντικείμενο τύπου HIBC LIC Data Matrix QR-Code.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Αντικείμενο τύπου HIBC LIC Aztec QR-Code.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Αντικείμενο τύπου HIBC PAS QR-Code.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Αντικείμενο τύπου HIBC PAS Data Matrix QR-Code.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Αντικείμενο τύπου HIBC PAS Aztec QR-Code.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Αντικείμενο τύπου Han Xin QR-Code.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Αντικείμενο τύπου GS1 Han Xin QR-Code.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Όλοι οι τύποι QRCode.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Επιστρέφει τύπο QRCode με όνομα pasringType. Εάν το όνομα του QRCode είναι άγνωστο - θα ριχτεί Exception.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | parsingType | java.lang.String | Κείμενο πηγής του ονόματος τύπου QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Επιστρέφει τύπο QRCode με το όνομα pasringType.
Εάν το όνομα του QRCode είναι άγνωστο - δεν θα ριχτεί Exception, αλλά η μέθοδος θα επιστρέψει τιμή null.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | parsingType | java.lang.String | Κείμενο πηγής του ονόματος τύπου QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Εσωτερική λίστα τύπων Decode για εξαγωγή.


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
