---
title: DigitalFormFieldSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains digital signature input form field properties for Pdf Documents.
type: docs
weight: 12
url: /java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Contains digital signature input form field properties for Pdf Documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Creates PdfDigitalFormFieldSignature with predefined name. |
## Methods

| Method | Description |
| --- | --- |
| [getSigned()](#getSigned--) | Read-only property that shows if Form-field Signature was signed with digital certificate. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone FormField Signature instance. |
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Creates PdfDigitalFormFieldSignature with predefined name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of form field object. |

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Read-only property that shows if Form-field Signature was signed with digital certificate.

**Returns:**
boolean
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
