---
title: BarcodeSignature
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Contains Barcode Signature properties.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Contains Barcode Signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Initialize BarcodeSignature object with signature identifier that was obtained after search process. |
| [BarcodeSignature()](#BarcodeSignature--) | Initialize BarcodeSignature with default parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Specifies the Barcode Encode Type. |
| [getText()](#getText--) | Specifies text of Barcode. |
| [getFormat()](#getFormat--) | Specifies the format of Barcode signature image. |
| [getContent()](#getContent--) | Specifies Barcode binary data image content of type  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Barcode Signature instance. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Initialize BarcodeSignature object with signature identifier that was obtained after search process. This unique identifier is used to find additional properties for this signature from document signature information layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | Unique signature identifier obtained by Sign or Search method of Signature class [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Initialize BarcodeSignature with default parameters.

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Specifies the Barcode Encode Type.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Specifies text of Barcode.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specifies the format of Barcode signature image.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specifies Barcode binary data image content of type  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). By default this property will not be set. Use property  BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)) to enable this feature.

**Returns:**
byte[]
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overwrites Equals method to compare signature properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Signature object to compare with. |

**Returns:**
boolean - Returns true if passed signature object has same type and all its properties are equal to this instance properties.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Overrides GetHashCode method

**Returns:**
int - Signature hash code
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone Barcode Signature instance.

**Returns:**
java.lang.Object - Returns cloned Barcode Signature instance.
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| image | java.awt.image.BufferedImage |  |

