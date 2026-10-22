---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示条形码验证选项。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

表示条形码验证选项。

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | 为条形码签名创建默认的验证选项。 |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | 使用验证文本创建默认的验证选项 |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 使用条形码类型验证创建默认的验证选项 |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 使用条形码类型验证和文本创建默认的验证选项 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | 获取或设置条形码类型验证。 |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 获取或设置条形码类型验证。 |
| [toString()](#toString--) | 重写转换为字符串的方法。 |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


为条形码签名创建默认的验证选项。

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


使用验证文本创建默认的验证选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 要验证的条形码文本 |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


使用条形码类型验证创建默认的验证选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | 条形码类型验证 |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


使用条形码类型验证和文本创建默认的验证选项

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 要验证的条形码文本 |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | 条形码类型验证 |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


获取或设置条形码类型验证。

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


获取或设置条形码类型验证。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


重写转换为字符串的方法。

**Returns:**
java.lang.String -
