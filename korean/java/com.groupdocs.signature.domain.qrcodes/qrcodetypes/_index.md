---
title: "QrCodeTypes"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "QR코드 유형 컨테이너."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

QR코드 유형 컨테이너.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec Barcode 유형 객체. |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix Barcode 유형 객체. |
|
|  | [QR](#QR) | QR Barcode 유형 객체. |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix Barcode 유형 객체. |
|
|  | [GS1QR](#GS1QR) | GS1 QR Barcode 유형 객체. |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code 유형 객체. |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code 유형 객체. |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code 유형 객체. |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code 유형 객체. |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code 유형 객체. |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code 유형 객체. |
|
|  | [HanXin](#HanXin) | Han Xin QR-Code 유형 객체. |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code 유형 객체. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | 모든 QRCode 유형. |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType 이름을 가진 QRCode 유형을 반환합니다. |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType 이름을 가진 QRCode 유형을 반환합니다. |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | 추출을 위한 디코드 유형 내부 목록 |
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


Aztec Barcode 유형 객체.


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix Barcode 유형 객체.


### QR {#QR}
```
public static final QrCodeType QR
```


QR Barcode 유형 객체.


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix Barcode 유형 객체.


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR Barcode 유형 객체.


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code 유형 객체.


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code 유형 객체.


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code 유형 객체.


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code 유형 객체.


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code 유형 객체.


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code 유형 객체.


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code 유형 객체.


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code 유형 객체.


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


모든 QRCode 유형.


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


pasringType 이름을 가진 QRCode 유형을 반환합니다. QRCode 이름이 알 수 없는 경우 - 예외가 발생합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | parsingType | java.lang.String | QRCode 유형 이름의 원본 문자열. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


pasringType 이름을 가진 QRCode 유형을 반환합니다.
QRCode 이름이 알 수 없는 경우 - 예외가 발생하지 않으며 메서드는 null 값을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | parsingType | java.lang.String | QRCode 유형 이름의 원본 문자열. |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


추출을 위한 디코드 유형 내부 목록


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 유형 | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 유형 | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
