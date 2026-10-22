---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "QRCode 类型容器。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

QRCode 类型容器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Aztec](#Aztec) | Aztec 条形码类型对象。 |
| [DataMatrix](#DataMatrix) | DataMatrix 条形码类型对象。 |
| [QR](#QR) | QR 条形码类型对象。 |
| [GS1DataMatrix](#GS1DataMatrix) | GS1 DataMatrix 条形码类型对象。 |
| [GS1QR](#GS1QR) | GS1 QR 条形码类型对象。 |
| [HIBCLICQR](#HIBCLICQR) | HIBC LIC QR-Code 类型对象。 |
| [HIBCLICDataMatrix](#HIBCLICDataMatrix) | HIBC LIC Data Matrix QR-Code 类型对象。 |
| [HIBCLICAztec](#HIBCLICAztec) | HIBC LIC Aztec QR-Code 类型对象。 |
| [HIBCPASQR](#HIBCPASQR) | HIBC PAS QR-Code 类型对象。 |
| [HIBCPASDataMatrix](#HIBCPASDataMatrix) | HIBC PAS Data Matrix QR-Code 类型对象。 |
| [HIBCPASAztec](#HIBCPASAztec) | HIBC PAS Aztec QR-Code 类型对象。 |
| [HanXin](#HanXin) | Han Xin QR-Code 类型对象。 |
| [GS1HanXin](#GS1HanXin) | GS1 Han Xin QR-Code 类型对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | 所有 QRCode 类型。 |
| [parse(String parsingType)](#parse-java.lang.String-) | 返回具有 pasringType 名称的 QRCode 类型。 |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | 返回具有 pasringType 名称的 QRCode 类型。 |
| [getDecodeTypes()](#getDecodeTypes--) | 用于提取的解码类型内部列表 |
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


Aztec 条形码类型对象。

### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


DataMatrix 条形码类型对象。

### QR {#QR}
```
public static final QrCodeType QR
```


QR 条形码类型对象。

### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


GS1 DataMatrix 条形码类型对象。

### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


GS1 QR 条形码类型对象。

### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


HIBC LIC QR-Code 类型对象。

### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


HIBC LIC Data Matrix QR-Code 类型对象。

### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


HIBC LIC Aztec QR-Code 类型对象。

### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


HIBC PAS QR-Code 类型对象。

### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


HIBC PAS Data Matrix QR-Code 类型对象。

### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


HIBC PAS Aztec QR-Code 类型对象。

### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


Han Xin QR-Code 类型对象。

### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


GS1 Han Xin QR-Code 类型对象。

### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


所有 QRCode 类型。

**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


返回具有 pasringType 名称的 QRCode 类型。如果 QRCode 的名称未知 - 将抛出异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | QRCode 类型名称的源字符串。 |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


返回具有 pasringType 名称的 QRCode 类型。如果 QRCode 的名称未知 - 不会抛出异常，但方法将返回 null 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | java.lang.String | QRCode 类型名称的源字符串。 |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


用于提取的解码类型内部列表

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
