---
title: PdfMetadataSignature
second_title: GroupDocs.Signature for Java API Reference
description: Contains Pdf Metadata signature properties.
type: docs
weight: 14
url: /java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Contains Pdf Metadata signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Creates Pdf Metadata signature with predefined name and empty value |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Creates Pdf Metadata signature with predefined values |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Creates Pdf Metadata signature with predefined values |
## Methods

| Method | Description |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | The prefix tag of Pdf Metadata signature name. |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | The prefix tag of Pdf Metadata signature name. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Metadata Signature instance. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone Pdf Metadata Signature instance with given value. |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Creates Pdf Metadata signature with predefined name and empty value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Pdf Metadata Signature name |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Creates Pdf Metadata signature with predefined values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of Metadata signature object |
| value | java.lang.Object | Value of Metadata signature |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Creates Pdf Metadata signature with predefined values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of Metadata signature object |
| value | java.lang.Object | Value of Metadata signature |
| tag | java.lang.String | Prefix tag of Metadata signature |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


The prefix tag of Pdf Metadata signature name. By default this property is set to "xmp". Possible values are

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


The prefix tag of Pdf Metadata signature name. By default this property is set to "xmp". Possible values are

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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


Clone Metadata Signature instance.

**Returns:**
java.lang.Object - Returns cloned Metadata Signature instance
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clone Pdf Metadata Signature instance with given value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Value for new cloned object. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
