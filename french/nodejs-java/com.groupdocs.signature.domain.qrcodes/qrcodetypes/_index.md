---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Conteneur des types QRCode."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
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
| [Aztec](#Aztec) | Objet du type de code-barres Aztec. |
| [DataMatrix](#DataMatrix) | Objet du type de code-barres DataMatrix. |
| [QR](#QR) | Objet du type de code-barres QR. |
| [GS1DataMatrix](#GS1DataMatrix) | Objet du type de code-barres GS1 DataMatrix. |
| [GS1QR](#GS1QR) | Objet du type de code-barres GS1 QR. |
| [HIBCLICQR](#HIBCLICQR) | Objet du type HIBC LIC QR-Code. |
| [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Objet du type HIBC LIC Data Matrix QR-Code. |
| [HIBCLICAztec](#HIBCLICAztec) | Objet du type HIBC LIC Aztec QR-Code. |
| [HIBCPASQR](#HIBCPASQR) | Objet du type HIBC PAS QR-Code. |
| [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Objet du type HIBC PAS Data Matrix QR-Code. |
| [HIBCPASAztec](#HIBCPASAztec) | Objet du type HIBC PAS Aztec QR-Code. |
| [HanXin](#HanXin) | Objet du type Han Xin QR-Code. |
| [GS1HanXin](#GS1HanXin) | Objet du type GS1 Han Xin QR-Code. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | Tous les types QRCode. |
| [parse(String parsingType)](#parse-java.lang.String-) | Renvoie le type QRCode avec le nom pasringType. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | Renvoie le type QRCode avec le nom pasringType. |
| [getDecodeTypes()](#getDecodeTypes--) | Liste interne des types de décodage pour l'extraction |
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


Objet du type de code-barres Aztec.

### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Objet du type de code-barres DataMatrix.

### QR {#QR}
```
public static final QrCodeType QR
```


Objet du type de code-barres QR.

### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Objet du type de code-barres GS1 DataMatrix.

### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Objet du type de code-barres GS1 QR.

### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Objet du type HIBC LIC QR-Code.

### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Objet du type HIBC LIC Data Matrix QR-Code.

### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Objet du type HIBC LIC Aztec QR-Code.

### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Objet du type HIBC PAS QR-Code.

### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Objet du type HIBC PAS Data Matrix QR-Code.

### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Objet du type HIBC PAS Aztec QR-Code.

### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Objet du type Han Xin QR-Code.

### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Objet du type GS1 Han Xin QR-Code.

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


Renvoie le type QRCode avec le nom pasringType. Si le nom du QRCode est inconnu - une Exception sera levée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Chaîne source du nom du type QRCode. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Renvoie le type QRCode avec le nom pasringType. Si le nom du QRCode est inconnu - aucune Exception ne sera levée mais la méthode renverra une valeur null.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parsingType | java.lang.String | Chaîne source du nom du type QRCode. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Liste interne des types de décodage pour l'extraction

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
booléen
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
