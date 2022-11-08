---
title: RadioButtonFormFieldSignature
second_title: GroupDocs.Signature for Java API Reference
description: Contains radio-button input form field signature properties.
type: docs
weight: 14
url: /java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Contains radio-button input form field signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Creates RadioButtonFieldSignature with predefined name. |
| [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Creates RadioButtonFieldSignature with predefined name and items list. |
| [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Creates RadioButtonFieldSignature with predefined name, items list and selected value. |
## Methods

| Method | Description |
| --- | --- |
| [getSelected()](#getSelected--) | Contains selected value. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Contains selected value. |
| [getItems()](#getItems--) | Get or set Radio buttons options list. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Get or set Radio buttons options list. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone FormField Signature instance. |
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Creates RadioButtonFieldSignature with predefined name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Creates RadioButtonFieldSignature with predefined name and items list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |
| items | java.util.List<java.lang.String> | Values of radio-button list. |

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Creates RadioButtonFieldSignature with predefined name, items list and selected value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |
| items | java.util.List<java.lang.String> | Values of radio-button list. |
| selected | java.lang.Object | Selected value. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Contains selected value.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Contains selected value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Get or set Radio buttons options list.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Get or set Radio buttons options list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<java.lang.String> |  |

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
