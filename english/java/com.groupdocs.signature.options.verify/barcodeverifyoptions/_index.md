---
title: BarcodeVerifyOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the Barcode verify options.
type: docs
weight: 10
url: /java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

Represents the Barcode verify options.

--------------------

 **Learn more**  **Learn more**

 *  Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document ][How to eVerification Barcode signatures in a document]
 *  Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: Advanced usage of eVerification Barcode signatures in a document and additional settings


[How to eVerification Barcode signatures in a document]: https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | Creates default Verification Option for Barcode Signature. |
| [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | Creates default Verification Option with verification text |
| [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Creates default Verification Option with Barcode Type verification |
| [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Creates default Verification Option with Barcode Type verification and text |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gets or sets Barcode Type verification. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Gets or sets Barcode Type verification. |
| [toString()](#toString--) | Overrides conversion to string. |
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


Creates default Verification Option for Barcode Signature.

### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


Creates default Verification Option with verification text

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Barcode text to verify |

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


Creates default Verification Option with Barcode Type verification

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode Type verification |

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


Creates default Verification Option with Barcode Type verification and text

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Barcode text to verify |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode Type verification |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Gets or sets Barcode Type verification.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Gets or sets Barcode Type verification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


Overrides conversion to string.

**Returns:**
java.lang.String - 
