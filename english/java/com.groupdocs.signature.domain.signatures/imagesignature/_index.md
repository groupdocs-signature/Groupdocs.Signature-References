---
title: ImageSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Image signature properties.
type: docs
weight: 13
url: /java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Contains Image signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Initialize ImageSignature object with signature identifier that was obtained after search process. |
| [ImageSignature()](#ImageSignature--) | Initialize ImageSignature with default parameters. |
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Specifies the size in bytes of signature image. |
| [setSize(int value)](#setSize-int-) | Specifies the size in bytes of signature image. |
| [getFormat()](#getFormat--) | Specifies the format of signature image. |
| [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifies the format of signature image. |
| [getContent()](#getContent--) | Specifies image binary data content of type  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Barcode Signature instance. |
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Initialize ImageSignature object with signature identifier that was obtained after search process. This unique identifier is used to find additional properties for this signature from document signature information layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | Unique signature identifier obtained by Sign or Search method of Signature class [Signature](../../com.groupdocs.signature/signature). |

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Initialize ImageSignature with default parameters.

### getSize() {#getSize--}
```
public final int getSize()
```


Specifies the size in bytes of signature image.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Specifies the size in bytes of signature image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Specifies the format of signature image.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Specifies the format of signature image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Specifies image binary data content of type  Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)). By default this property will not be set. Use property  ImageSearchOptions.ReturnContent (\{ ImageSearchOptions\#getReturnContent\}/\{ ImageSearchOptions\#setReturnContent(boolean)\}) to enable this feature.

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
