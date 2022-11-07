---
title: TextSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Text signature properties.
type: docs
weight: 16
url: /java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Contains Text signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Initialize TextSignature object with signature identifier that was obtained after search process. |
| [TextSignature()](#TextSignature--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Specifies text in signature. |
| [setText(String value)](#setText-java.lang.String-) | Specifies text in signature. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Specifies text signature implementation. |
| [getNative()](#getNative--) | Specifies the native attribute. |
| [setNative(boolean value)](#setNative-boolean-) | Specifies the native attribute. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Text Signature instance. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Initialize TextSignature object with signature identifier that was obtained after search process. This unique identifier is used to find additional properties for this signature from document signature information layer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | Unique signature identifier obtained by sign or search method. |

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Specifies text in signature.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifies text in signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Specifies text signature implementation.

**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Specifies the native attribute. It is true if signature is document-specific.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Specifies the native attribute. It is true if signature is document-specific.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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


Clone Text Signature instance.

**Returns:**
java.lang.Object - Returns cloned Text Signature instance.
