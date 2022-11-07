---
title: PresentationMetadataSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Presentation metadata signature properties.
type: docs
weight: 15
url: /java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Contains Presentation metadata signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | Creates Presentation Metadata Signature with predefined name and empty value |
| [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | Creates Presentation Metadata Signature with predefined values |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clone Metadata Signature instance. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Clone Slides Metadata Signature instance with given value. |
| [toString()](#toString--) | Converts to String with override ToString() method |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | Converts to String with specified format |
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


Creates Presentation Metadata Signature with predefined name and empty value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Presentation Metadata Signature name |

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


Creates Presentation Metadata Signature with predefined values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of Metadata signature object |
| value | java.lang.Object | Value of Metadata signature |

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


Clone Slides Metadata Signature instance with given value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Value for new cloned object. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


Converts to String with override ToString() method

**Returns:**
java.lang.String - Returns the Metadata Signature value as String.

--------------------

Converts a boolean property into "True" or "False". For another data type the default data format provider will be used.
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


Converts to String with specified format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | java.lang.String | Data format string. |
| provider | com.aspose.ms.System.IFormatProvider | Format data provider to use with data conversion operations.

--------------------

Converts a boolean property into "True" or "False". |

**Returns:**
java.lang.String - Returns the Metadata Signature value as String.
