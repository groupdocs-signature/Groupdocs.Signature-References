---
title: BaseSignature
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Describes base class for signatures.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Describes base class for signatures.
## Methods

| Method | Description |
| --- | --- |
| [getSignatureType()](#getSignatureType--) | Specifies the type of signature. |
| [getPageNumber()](#getPageNumber--) | Specifies the page signature was found on. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Specifies the page signature was found on. |
| [getSignatureId()](#getSignatureId--) | Unique signature identifier to modify signature in the document over Update or Delete methods. |
| [isSignature()](#isSignature--) | Get or set flag to indicate if this component is Signature or document content. |
| [setSignature(boolean value)](#setSignature-boolean-) | Get or set flag to indicate if this component is Signature or document content. |
| [getDeleted()](#getDeleted--) | Get or set flag to indicate if this signature was deleted from the document. |
| [getCreatedOn()](#getCreatedOn--) | Get or set the signature creation date. |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Get or set the signature creation date. |
| [getModifiedOn()](#getModifiedOn--) | Get or set the signature modification date. |
| [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Get or set the signature modification date. |
| [getTop()](#getTop--) | Specifies top position of signature. |
| [setTop(int value)](#setTop-int-) | Specifies top position of signature. |
| [getLeft()](#getLeft--) | Specifies left position of signature. |
| [setLeft(int value)](#setLeft-int-) | Specifies left position of signature. |
| [getWidth()](#getWidth--) | Specifies width of signature. |
| [setWidth(int value)](#setWidth-int-) | Specifies width of signature. |
| [getHeight()](#getHeight--) | Specifies height of signature. |
| [setHeight(int value)](#setHeight-int-) | Specifies height of signature. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
| [toString()](#toString--) |  |
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Specifies the type of signature. Digital signature will have this property.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Specifies the page signature was found on.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Specifies the page signature was found on.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Unique signature identifier to modify signature in the document over Update or Delete methods. This property will be set automatically after Sign or Search method being called. If this property was saved before it can be set manually to manipulate the signature.

**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Get or set flag to indicate if this component is Signature or document content. This property is being used with Update method to set element as signature (true) or document element (false).

**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Get or set flag to indicate if this component is Signature or document content. This property is being used with Update method to set element as signature (true) or document element (false).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Get or set flag to indicate if this signature was deleted from the document. This property is being used only for document history log records to keep the list of deleted signatures.

**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Get or set the signature creation date.

**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Get or set the signature creation date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Get or set the signature modification date.

**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Get or set the signature modification date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Specifies top position of signature.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Specifies top position of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Specifies left position of signature.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Specifies left position of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Specifies width of signature.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Specifies width of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Specifies height of signature.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Specifies height of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
int - 
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String - 
