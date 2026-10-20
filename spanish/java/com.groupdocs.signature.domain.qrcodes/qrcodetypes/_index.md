---
title: "QrCodeTypes"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contenedor de tipos de códigos QR."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Contenedor de tipos de códigos QR.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Aztec](#Aztec) | Objeto de tipo de código de barras Aztec. |
|
|  | [DataMatrix](#DataMatrix) | Objeto de tipo de código de barras DataMatrix. |
|
|  | [QR](#QR) | Objeto de tipo de código de barras QR. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | Objeto de tipo de código de barras GS1 DataMatrix. |
|
|  | [GS1QR](#GS1QR) | Objeto de tipo de código de barras GS1 QR. |
|
|  | [HIBCLICQR](#HIBCLICQR) | Objeto del tipo HIBC LIC QR-Code. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Objeto del tipo HIBC LIC Data Matrix QR-Code. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | Objeto del tipo HIBC LIC Aztec QR-Code. |
|
|  | [HIBCPASQR](#HIBCPASQR) | Objeto del tipo HIBC PAS QR-Code. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Objeto del tipo HIBC PAS Data Matrix QR-Code. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | Objeto de tipo QR-Code HIBC PAS Aztec. |
|
|  | [HanXin](#HanXin) | Objeto de tipo QR-Code Han Xin. |
|
|  | [GS1HanXin](#GS1HanXin) | Objeto de tipo QR-Code GS1 Han Xin. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Todos los tipos de QRCode. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Devuelve el tipo QRCode con el nombre pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Devuelve el tipo QRCode con el nombre pasringType. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Lista interna de tipos de decodificación para extracción |
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


Objeto de tipo de código de barras Aztec.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Objeto de tipo de código de barras DataMatrix.


### QR {#QR}
```
public static final QrCodeType QR
```


Objeto de tipo de código de barras QR.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Objeto de tipo de código de barras GS1 DataMatrix.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Objeto de tipo de código de barras GS1 QR.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Objeto del tipo HIBC LIC QR-Code.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Objeto del tipo HIBC LIC Data Matrix QR-Code.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Objeto del tipo HIBC LIC Aztec QR-Code.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Objeto del tipo HIBC PAS QR-Code.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Objeto del tipo HIBC PAS Data Matrix QR-Code.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Objeto de tipo QR-Code HIBC PAS Aztec.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Objeto de tipo QR-Code Han Xin.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Objeto de tipo QR-Code GS1 Han Xin.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Todos los tipos de QRCode.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Devuelve el tipo QRCode con el nombre pasringType. Si el nombre del QRCode es desconocido, se lanzará una excepción.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | parsingType | java.lang.String | Cadena de origen del nombre del tipo QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Devuelve el tipo QRCode con el nombre pasringType.
Si el nombre del QRCode es desconocido, no se lanzará una excepción, pero el método devolverá un valor nulo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | parsingType | java.lang.String | Cadena de origen del nombre del tipo QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Lista interna de tipos de decodificación para extracción


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
