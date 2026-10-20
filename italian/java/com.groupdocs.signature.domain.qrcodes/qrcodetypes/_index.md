---
title: "QrCodeTypes"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Contenitore dei tipi QRCode."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Contenitore dei tipi QRCode.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Aztec](#Aztec) | Oggetto del tipo di codice a barre Aztec. |
|
|  | [DataMatrix](#DataMatrix) | Oggetto del tipo di codice a barre DataMatrix. |
|
|  | [QR](#QR) | Oggetto del tipo di codice a barre QR. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | Oggetto del tipo di codice a barre GS1 DataMatrix. |
|
|  | [GS1QR](#GS1QR) | Oggetto del tipo di codice a barre GS1 QR. |
|
|  | [HIBCLICQR](#HIBCLICQR) | Oggetto del tipo HIBC LIC QR-Code. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Oggetto del tipo HIBC LIC Data Matrix QR-Code. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | Oggetto del tipo HIBC LIC Aztec QR-Code. |
|
|  | [HIBCPASQR](#HIBCPASQR) | Oggetto del tipo HIBC PAS QR-Code. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Oggetto del tipo HIBC PAS Data Matrix QR-Code. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | Oggetto del tipo HIBC PAS Aztec QR-Code. |
|
|  | [HanXin](#HanXin) | Oggetto del tipo Han Xin QR-Code. |
|
|  | [GS1HanXin](#GS1HanXin) | Oggetto del tipo GS1 Han Xin QR-Code. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Tutti i tipi QRCode. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Restituisce il tipo QRCode con il nome pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Restituisce il tipo QRCode con il nome pasringType. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Elenco interno di tipi di decodifica per l'estrazione |
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


Oggetto del tipo di codice a barre Aztec.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Oggetto del tipo di codice a barre DataMatrix.


### QR {#QR}
```
public static final QrCodeType QR
```


Oggetto del tipo di codice a barre QR.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Oggetto del tipo di codice a barre GS1 DataMatrix.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Oggetto del tipo di codice a barre GS1 QR.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Oggetto del tipo HIBC LIC QR-Code.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Oggetto del tipo HIBC LIC Data Matrix QR-Code.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Oggetto del tipo HIBC LIC Aztec QR-Code.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Oggetto del tipo HIBC PAS QR-Code.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Oggetto del tipo HIBC PAS Data Matrix QR-Code.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Oggetto del tipo HIBC PAS Aztec QR-Code.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Oggetto del tipo Han Xin QR-Code.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Oggetto del tipo GS1 Han Xin QR-Code.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Tutti i tipi QRCode.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Restituisce il tipo QRCode con il nome pasringType. Se il nome del QRCode è sconosciuto - verrà lanciata un'Exception


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parsingType | java.lang.String | Stringa di origine del nome del tipo QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Restituisce il tipo QRCode con il nome pasringType.
Se il nome del QRCode è sconosciuto - non verrà lanciata alcuna Exception ma il metodo restituirà un valore null.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parsingType | java.lang.String | Stringa di origine del nome del tipo QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Elenco interno di tipi di decodifica per l'estrazione


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tipo | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
