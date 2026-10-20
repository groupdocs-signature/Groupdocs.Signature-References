---
title: "QrCodeTypes"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "QRコードタイプのコンテナです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

QRコードタイプのコンテナです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Aztec](#Aztec) | Aztec バーコードタイプオブジェクト。 |
|
|  | [DataMatrix](#DataMatrix) | DataMatrix バーコードタイプオブジェクト。 |
|
|  | [QR](#QR) | QR バーコードタイプオブジェクト。 |
|
|  | [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix バーコードタイプオブジェクト。 |
|
|  | [GS1QR](#GS1QR) | GS1 QR バーコードタイプオブジェクト。 |
|
|  | [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code タイプオブジェクト。 |
|
|  | [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code タイプオブジェクト。 |
|
|  | [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code タイプオブジェクト。 |
|
|  | [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code タイプオブジェクト。 |
|
|  | [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code タイプオブジェクト。 |
|
|  | [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code タイプオブジェクト。 |
|
|  | [HanXin](#HanXin) | Han Xin QR-Code タイプオブジェクト。 |
|
|  | [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code タイプオブジェクト。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | すべての QRCode タイプ。 |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType 名で QRCode タイプを返します。 |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType 名で QRCode タイプを返します。 |
|
|  | [getDecodeTypes()](#getDecodeTypes--) | 抽出用のデコードタイプの内部リスト |
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


Aztec バーコードタイプオブジェクト。


### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix バーコードタイプオブジェクト。


### QR {#QR}
```
public static final QrCodeType QR
```


QR バーコードタイプオブジェクト。


### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix バーコードタイプオブジェクト。


### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR バーコードタイプオブジェクト。


### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code タイプオブジェクト。


### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code タイプオブジェクト。


### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code タイプオブジェクト。


### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code タイプオブジェクト。


### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code タイプオブジェクト。


### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code タイプオブジェクト。


### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code タイプオブジェクト。


### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code タイプオブジェクト。


### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


すべての QRCode タイプ。


**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


pasringType 名で QRCode タイプを返します。QRCode の名前が不明な場合は例外がスローされます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | parsingType | java.lang.String | QRCode タイプ名のソース文字列。 |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


pasringType 名で QRCode タイプを返します。
QRCode の名前が不明な場合、例外はスローされず、メソッドは null 値を返します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | parsingType | java.lang.String | QRCode タイプ名のソース文字列。 |
|

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.

### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


抽出用のデコードタイプの内部リスト


**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タイプ | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タイプ | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
