---
title: "QrCodeTypes"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "حاوية أنواع رمز QR."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.domain.qrcodes/qrcodetypes/
---
**Inheritance:**
java.lang.Object
```
public class QrCodeTypes
```

حاوية أنواع رمز QR.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [QrCodeTypes()](#QrCodeTypes--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Aztec](#Aztec) | كائن نوع الباركود Aztec. |
| [DataMatrix](#DataMatrix) | كائن نوع الباركود DataMatrix. |
| [QR](#QR) | كائن نوع الباركود QR. |
| [GS1DataMatrix](#GS1DataMatrix) | كائن نوع الباركود GS1 DataMatrix. |
| [GS1QR](#GS1QR) | كائن نوع الباركود GS1 QR. |
| [HIBCLICQR](#HIBCLICQR) | كائن نوع QR-Code HIBC LIC. |
| [HIBCLICDataMatrix](#HIBCLICDataMatrix) | كائن نوع QR-Code Data Matrix HIBC LIC. |
| [HIBCLICAztec](#HIBCLICAztec) | كائن نوع QR-Code Aztec HIBC LIC. |
| [HIBCPASQR](#HIBCPASQR) | كائن نوع QR-Code HIBC PAS. |
| [HIBCPASDataMatrix](#HIBCPASDataMatrix) | كائن نوع QR-Code Data Matrix HIBC PAS. |
| [HIBCPASAztec](#HIBCPASAztec) | كائن نوع QR-Code Aztec HIBC PAS. |
| [HanXin](#HanXin) | كائن نوع QR-Code Han Xin. |
| [GS1HanXin](#GS1HanXin) | كائن نوع QR-Code GS1 Han Xin. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAllTypes()](#getAllTypes--) | جميع أنواع QRCode. |
| [parse(String parsingType)](#parse-java.lang.String-) | يعيد نوع QRCode بالاسم pasringType. |
| [tryParse(String parsingType)](#tryParse-java.lang.String-) | يعيد نوع QRCode بالاسم pasringType. |
| [getDecodeTypes()](#getDecodeTypes--) | قائمة داخلية لأنواع فك الترميز للاستخراج |
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


كائن نوع الباركود Aztec.

### DataMatrix {#DataMatrix}
```
public static final QrCodeType DataMatrix
```


كائن نوع الباركود DataMatrix.

### QR {#QR}
```
public static final QrCodeType QR
```


كائن نوع الباركود QR.

### GS1DataMatrix {#GS1DataMatrix}
```
public static final QrCodeType GS1DataMatrix
```


كائن نوع الباركود GS1 DataMatrix.

### GS1QR {#GS1QR}
```
public static final QrCodeType GS1QR
```


كائن نوع الباركود GS1 QR.

### HIBCLICQR {#HIBCLICQR}
```
public static final QrCodeType HIBCLICQR
```


كائن نوع QR-Code HIBC LIC.

### HIBCLICDataMatrix {#HIBCLICDataMatrix}
```
public static final QrCodeType HIBCLICDataMatrix
```


كائن نوع QR-Code Data Matrix HIBC LIC.

### HIBCLICAztec {#HIBCLICAztec}
```
public static final QrCodeType HIBCLICAztec
```


كائن نوع QR-Code Aztec HIBC LIC.

### HIBCPASQR {#HIBCPASQR}
```
public static final QrCodeType HIBCPASQR
```


كائن نوع QR-Code HIBC PAS.

### HIBCPASDataMatrix {#HIBCPASDataMatrix}
```
public static final QrCodeType HIBCPASDataMatrix
```


كائن نوع QR-Code Data Matrix HIBC PAS.

### HIBCPASAztec {#HIBCPASAztec}
```
public static final QrCodeType HIBCPASAztec
```


كائن نوع QR-Code Aztec HIBC PAS.

### HanXin {#HanXin}
```
public static final QrCodeType HanXin
```


كائن نوع QR-Code Han Xin.

### GS1HanXin {#GS1HanXin}
```
public static final QrCodeType GS1HanXin
```


كائن نوع QR-Code GS1 Han Xin.

### getAllTypes() {#getAllTypes--}
```
public static QrCodeType[] getAllTypes()
```


جميع أنواع QRCode.

**Returns:**
com.groupdocs.signature.domain.qrcodes.QrCodeType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static QrCodeType parse(String parsingType)
```


يعيد نوع QRCode بالاسم pasringType. إذا كان اسم QRCode غير معروف - سيتم رمي الاستثناء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة المصدر لاسم نوع QRCode. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static QrCodeType tryParse(String parsingType)
```


يعيد نوع QRCode بالاسم pasringType. إذا كان اسم QRCode غير معروف - لن يتم رمي استثناء ولكن ستعيد الطريقة قيمة null.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة المصدر لاسم نوع QRCode. |

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) - QRCodeType instance.
### getDecodeTypes() {#getDecodeTypes--}
```
public static System.Collections.Generic.List<BaseDecodeType> getDecodeTypes()
```


قائمة داخلية لأنواع فك الترميز للاستخراج

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.barcoderecognition.BaseDecodeType>
### isComplexType(System.Type type, QrCodeType qrCodeType) {#isComplexType-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static boolean isComplexType(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
boolean
### getDataEncoding(System.Type type, QrCodeType qrCodeType) {#getDataEncoding-com.aspose.ms.System.Type-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public static IComplexCodeDataEncoding getDataEncoding(System.Type type, QrCodeType qrCodeType)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نوع | com.aspose.ms.System.Type |  |
| qrCodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

**Returns:**
[IComplexCodeDataEncoding](../../com.groupdocs.signature.domain.extensions/icomplexcodedataencoding)
