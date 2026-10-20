---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Контейнер типов QR‑кодов."
type: docs
weight: 11
url: /ru/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

Контейнер типов QR‑кодов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [Aztec](#Aztec) | Объект типа штрих‑кода Aztec. |
|
|  | [DataMatrix](#DataMatrix) | Объект типа штрих‑кода DataMatrix. |
|
|  | [QR](#QR) | Объект типа штрих‑кода QR. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | Объект типа штрих‑кода GS1 DataMatrix. |
|
|  | [GS1QR](#GS1QR) | Объект типа штрих‑кода GS1 QR. |
|
|  | [HIBCLICQR](#HIBCLICQR) | Объект типа QR‑кода HIBC LIC. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | Объект типа QR‑кода HIBC LIC Data Matrix. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | Объект типа QR‑кода HIBC LIC Aztec. |
|
|  | [HIBCPASQR](#HIBCPASQR) | Объект типа QR‑кода HIBC PAS. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | Объект типа QR‑кода HIBC PAS Data Matrix. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | Объект типа QR‑кода HIBC PAS Aztec. |
|
|  | [HanXin](#HanXin) | Объект типа QR‑кода Han Xin. |
|
|  | [GS1HanXin](#GS1HanXin) | Объект типа QR‑кода GS1 Han Xin. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | Все типы QRCode. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | Возвращает тип QRCode с именем pasringType. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | Возвращает тип QRCode с именем pasringType. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | Внутренний список типов Decode для извлечения |
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


Объект типа штрих‑кода Aztec.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


Объект типа штрих‑кода DataMatrix.


### QR {#QR}
```
public static final QrCodeType QR
```


Объект типа штрих‑кода QR.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


Объект типа штрих‑кода GS1 DataMatrix.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


Объект типа штрих‑кода GS1 QR.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


Объект типа QR‑кода HIBC LIC.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


Объект типа QR‑кода HIBC LIC Data Matrix.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


Объект типа QR‑кода HIBC LIC Aztec.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


Объект типа QR‑кода HIBC PAS.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


Объект типа QR‑кода HIBC PAS Data Matrix.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


Объект типа QR‑кода HIBC PAS Aztec.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Объект типа QR‑кода Han Xin.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


Объект типа QR‑кода GS1 Han Xin.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


Все типы QRCode.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


Возвращает тип QRCode с именем pasringType. Если имя QRCode неизвестно — будет выброшено исключение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | parsingType | java.lang.String | Исходная строка имени типа QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


Возвращает тип QRCode с именем pasringType.
Если имя QRCode неизвестно — исключение не будет выброшено, но метод вернёт значение null.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | parsingType | java.lang.String | Исходная строка имени типа QRCode. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


Внутренний список типов Decode для извлечения


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
