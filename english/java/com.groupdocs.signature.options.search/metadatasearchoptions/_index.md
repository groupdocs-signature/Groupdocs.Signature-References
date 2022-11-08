---
title: MetadataSearchOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents abstract search Options for Metadata signatures.
type: docs
weight: 14
url: /java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Represents abstract search Options for Metadata signatures.
## Constructors

| Constructor | Description |
| --- | --- |
| [MetadataSearchOptions()](#MetadataSearchOptions--) | Initializes a new instance of the SearchMetadataOptions class with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Specifies Metadata Signature name if it should be searched and matched. |
| [setName(String value)](#setName-java.lang.String-) | Specifies Metadata Signature name if it should be searched and matched. |
| [getNameMatchType()](#getNameMatchType--) | Gets or sets Metadata name Match Type search. |
| [setNameMatchType(int value)](#setNameMatchType-int-) | Gets or sets Metadata name Match Type search. |
| [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Indicates if Built-in document properties like Document statistic, information etc should be included into Search result. |
| [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Indicates if Built-in document properties like Document statistic, information etc should be included into Search result. |
| [getDataEncryption()](#getDataEncryption--) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties. |
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Initializes a new instance of the SearchMetadataOptions class with default values.

### getName() {#getName--}
```
public final String getName()
```


Specifies Metadata Signature name if it should be searched and matched.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifies Metadata Signature name if it should be searched and matched.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Gets or sets Metadata name Match Type search. It is used only when Name property is set.

**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Gets or sets Metadata name Match Type search. It is used only when Name property is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Indicates if Built-in document properties like Document statistic, information etc should be included into Search result. This flag has sense for Presentation, Spreadhsheet and Word Processing document file types.

**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Indicates if Built-in document properties like Document statistic, information etc should be included into Search result. This flag has sense for Presentation, Spreadhsheet and Word Processing document file types.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Gets or sets implementation of [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) interface to encode and decode QR-Code Signature Text or Data properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

