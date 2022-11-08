---
title: ComboboxFormFieldSignature
second_title: GroupDocs.Signature for Java API Reference
description: Contains combo-box input form field signature properties.
type: docs
weight: 11
url: /java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Contains combo-box input form field signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Creates ComboboxFormFieldSignature with predefined name. |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Creates ComboboxFormFieldSignature with predefined name and options list. |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Creates ComboboxFormFieldSignature with predefined name, options list and selected value. |
## Methods

| Method | Description |
| --- | --- |
| [getSelected()](#getSelected--) | Get or set selected value. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Get or set selected value. |
| [getItems()](#getItems--) | Get or set combo-box options list. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Get or set combo-box options list. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone FormField Signature instance. |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Creates ComboboxFormFieldSignature with predefined name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Creates ComboboxFormFieldSignature with predefined name and options list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |
| items | java.util.List<java.lang.String> | Values of combo-box list. |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Creates ComboboxFormFieldSignature with predefined name, options list and selected value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |
| items | java.util.List<java.lang.String> | Values of combo-box list. |
| selected | java.lang.Object | Selected value. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Get or set selected value.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Get or set selected value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Get or set combo-box options list.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Get or set combo-box options list.

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
