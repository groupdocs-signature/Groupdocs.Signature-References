---
title: MetadataSignatureCollection
second_title: GroupDocs.Signature for Java API Reference
description: Collection of Metadata signature objects.
type: docs
weight: 13
url: /java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Collection of Metadata signature objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Creates Collection of Metadata signature. |
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets number of items in the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
| [contains(String name)](#contains-java.lang.String-) | Returns true if a Metadata with the specified name exists in the collection. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Gets the index of a property by name. |
| [remove(String name)](#remove-java.lang.String-) | Removes a Metadata Signature with the specified name from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a Metadata Signature at the specified index. |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Add Metadata Signature object to collection. |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Add Metadata Signature collection. |
| [deepClone()](#deepClone--) | Clone Metadata Signature Collection class with Metadata Signature Items. |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Creates Collection of Metadata signature.

### getCount() {#getCount--}
```
public final int getCount()
```


Gets number of items in the collection.

**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Removes all items from the collection.

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Returns true if a Metadata with the specified name exists in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of the property. |

**Returns:**
boolean - True if the Metadata exists in the collection; false otherwise.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Gets the index of a property by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of the MetadataSignature. |

**Returns:**
int - The zero based index. Negative value if not found.
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Removes a Metadata Signature with the specified name from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The case-insensitive name of the Metadata Signature. |

**Returns:**
boolean - 
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Removes a Metadata Signature at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero based index. |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Add Metadata Signature object to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Metadata signature to be added to collection.

--------------------

Throws an exception if name value is not unique entire existing collection |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Add Metadata Signature collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Collection of signatures to add.

--------------------

Throws an exception if name value is not unique entire existing collection |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clone Metadata Signature Collection class with Metadata Signature Items.

**Returns:**
java.lang.Object - Returns copied instance with cloned Signature Items
