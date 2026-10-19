---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Container für QRCode-Typen."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Container für QRCode-Typen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec Barcode Typ-Objekt. |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix Barcode Typ-Objekt. |
|
|  | [QR](#QR) | QR Barcode Typ-Objekt. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix Barcode Typ-Objekt. |
|
|  | [GS1QR](#GS1QR) | GS1 QR Barcode Typ-Objekt. |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code Typ-Objekt. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code Typ-Objekt. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code Typ-Objekt. |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code Typ-Objekt. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code Typ-Objekt. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code Typ-Objekt. |
|
|  | [HanXin](#HanXin) | Han Xin QR-Code Typ-Objekt. |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code Typ-Objekt. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Alle QRCode-Typen. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Gibt den QRCode-Typ mit dem Namen pasringType zurück. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Gibt den QRCode-Typ mit dem Namen pasringType zurück. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Interne Liste der Dekodier-Typen für die Extraktion |
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


Aztec Barcode Typ-Objekt.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix Barcode Typ-Objekt.


### QR {#QR}
```
public static final QrCodeType QR
```


QR Barcode Typ-Objekt.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix Barcode Typ-Objekt.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR Barcode Typ-Objekt.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code Typ-Objekt.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code Typ-Objekt.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code Typ-Objekt.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code Typ-Objekt.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code Typ-Objekt.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code Typ-Objekt.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code Typ-Objekt.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code Typ-Objekt.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Alle QRCode-Typen.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Gibt den QRCode-Typ mit dem Namen pasringType zurück. Wenn der Name des QRCode unbekannt ist – wird eine Exception ausgelöst.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | parsingType | java.lang.String | Quellzeichenfolge des QRCode-Typnamens. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Gibt den QRCode-Typ mit dem Namen pasringType zurück.
Wenn der Name des QRCode unbekannt ist – wird keine Exception ausgelöst, aber die Methode gibt einen Nullwert zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | parsingType | java.lang.String | Quellzeichenfolge des QRCode-Typnamens. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Interne Liste der Dekodier-Typen für die Extraktion


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
