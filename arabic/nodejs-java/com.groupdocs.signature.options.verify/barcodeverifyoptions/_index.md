---
title: "BarcodeVerifyOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات التحقق من Barcode."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

يمثل خيارات التحقق من Barcode.

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | ينشئ خيار التحقق الافتراضي لتوقيع الباركود. |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | ينشئ خيار التحقق الافتراضي مع نص التحقق |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود والنص |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | يحصل أو يعيّن تحقق نوع الباركود. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | يحصل أو يعيّن تحقق نوع الباركود. |
| [toString()](#toString--) | يتجاوز التحويل إلى سلسلة. |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


ينشئ خيار التحقق الافتراضي لتوقيع الباركود.

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


ينشئ خيار التحقق الافتراضي مع نص التحقق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String | نص الباركود للتحقق |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | تحقق نوع الباركود |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود والنص

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نص | java.lang.String | نص الباركود للتحقق |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | تحقق نوع الباركود |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


يحصل أو يعيّن تحقق نوع الباركود.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


يحصل أو يعيّن تحقق نوع الباركود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى سلسلة.

**Returns:**
java.lang.String -
