---
title: "QrCodeTypes"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Conteneur des types QRCode."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Conteneur des types QRCode.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [Aztec](#Aztec) | Objet de type de code-barres Aztec. |
|
|  | [DataMatrix](#DataMatrix) | Objet de type de code-barres DataMatrix. |
|
|  | [QR](#QR) | Objet de type de code-barres QR. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | Objet de type de code-barres GS1 DataMatrix. |
|
|  | [GS1QR](#GS1QR) | Objet de type de code-barres GS1 QR. |
|
|  | [HIBCLICQR](#HIBCLICQR) | Objet de type HIBC LIC QR-Code. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Objet de type HIBC LIC Data Matrix QR-Code. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | Objet de type HIBC LIC Aztec QR-Code. |
|
|  | [HIBCPASQR](#HIBCPASQR) | Objet de type HIBC PAS QR-Code. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Objet de type HIBC PAS Data Matrix QR-Code. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | Objet de type HIBC PAS Aztec QR-Code. |
|
|  | [HanXin](#HanXin) | Objet de type Han Xin QR-Code. |
|
|  | [GS1HanXin](#GS1HanXin) | Objet de type GS1 Han Xin QR-Code. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Tous les types QRCode. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Retourne le type QRCode avec le nom pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Retourne le type QRCode avec le nom pasringType. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Liste interne des types de décodage pour l'extraction. |
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


Objet de type de code-barres Aztec.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Objet de type de code-barres DataMatrix.


### QR {#QR}
```
public static final QrCodeType QR
```


Objet de type de code-barres QR.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Objet de type de code-barres GS1 DataMatrix.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Objet de type de code-barres GS1 QR.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Objet de type HIBC LIC QR-Code.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Objet de type HIBC LIC Data Matrix QR-Code.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Objet de type HIBC LIC Aztec QR-Code.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Objet de type HIBC PAS QR-Code.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Objet de type HIBC PAS Data Matrix QR-Code.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Objet de type HIBC PAS Aztec QR-Code.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Objet de type Han Xin QR-Code.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Objet de type GS1 Han Xin QR-Code.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Tous les types QRCode.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Retourne le type QRCode avec le nom pasringType. Si le nom du QRCode est inconnu - une Exception sera levée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | parsingType | java.lang.String | Chaîne source du nom du type QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Retourne le type QRCode avec le nom pasringType.
Si le nom du QRCode est inconnu - aucune Exception ne sera levée mais la méthode renverra une valeur null.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | parsingType | java.lang.String | Chaîne source du nom du type QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Liste interne des types de décodage pour l'extraction.


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| type | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
