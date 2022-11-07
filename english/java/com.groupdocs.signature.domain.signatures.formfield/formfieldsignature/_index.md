---
title: FormFieldSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Form field signature properties.
type: docs
weight: 13
url: /java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Contains Form field signature properties.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Specifies unique form field name. |
| [setName(String value)](#setName-java.lang.String-) | Specifies unique form field name. |
| [getType()](#getType--) | Specifies Form field type. |
| [getValue()](#getValue--) | Specifies Form field data object. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Specifies Form field data object. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone FormField Signature instance. |
### getName() {#getName--}
```
public final String getName()
```


Specifies unique form field name.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifies unique form field name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Specifies Form field type.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Specifies Form field data object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Specifies Form field data object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

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


Clone FormField Signature instance.

**Returns:**
java.lang.Object - Returns cloned FormField Signature instance.
