---
title: CheckboxFormFieldSignature
second_title: GroupDocs.Signature for Java API Reference
description: Contains check-box input form field signature properties.
type: docs
weight: 10
url: /java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Contains check-box input form field signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Creates PdfCheckboxFormFieldSignature with predefined name. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Creates PdfCheckboxFormFieldSignature with predefined name and value |
## Methods

| Method | Description |
| --- | --- |
| [getChecked()](#getChecked--) | Gets or sets checked value of form field check-box input. |
| [setChecked(boolean value)](#setChecked-boolean-) | Gets or sets checked value of form field check-box input. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone FormField Signature instance. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Creates PdfCheckboxFormFieldSignature with predefined name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Creates PdfCheckboxFormFieldSignature with predefined name and value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |
| isChecked | boolean | Value if check box is checked |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Gets or sets checked value of form field check-box input.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Gets or sets checked value of form field check-box input.

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


Clone FormField Signature instance.

**Returns:**
java.lang.Object - Returns cloned FormField Signature instance.
