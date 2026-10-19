---
title: "BarcodeVerifyOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات التحقق من الباركود."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

يمثل خيارات التحقق من الباركود.

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | ينشئ خيار التحقق الافتراضي لتوقيع الباركود. |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | ينشئ خيار التحقق الافتراضي مع نص التحقق |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود والنص |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | الحصول أو تعيين التحقق من نوع الباركود. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | الحصول أو تعيين التحقق من نوع الباركود. |
|
|  | [toString()](#toString--) | يتجاوز التحويل إلى string. |
|
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
|  | نص | java.lang.String | نص الباركود للتحقق |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | التحقق من نوع الباركود |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


ينشئ خيار التحقق الافتراضي مع تحقق نوع الباركود والنص


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | نص الباركود للتحقق |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | التحقق من نوع الباركود |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


الحصول أو تعيين التحقق من نوع الباركود.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


الحصول أو تعيين التحقق من نوع الباركود.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى string.


**Returns:**
java.lang.String -
