---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen voor een selectievakje invoerveldhandtekening."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Bevat eigenschappen voor een selectievakje invoerveldhandtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Maakt PdfCheckboxFormFieldSignature aan met een vooraf gedefinieerde naam. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Maakt PdfCheckboxFormFieldSignature aan met een vooraf gedefinieerde naam en waarde. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getChecked()](#getChecked--) | Haalt de aangevinkte waarde op of stelt deze in van de invoer van het formulier‑check‑box. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | Haalt de aangevinkte waarde op of stelt deze in van de invoer van het formulier‑check‑box. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon FormField Signature‑instantie. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Maakt PdfCheckboxFormFieldSignature aan met een vooraf gedefinieerde naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Maakt PdfCheckboxFormFieldSignature aan met een vooraf gedefinieerde naam en waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|
|  | isChecked | boolean | Waarde als het selectievakje is aangevinkt |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Haalt de aangevinkte waarde op of stelt deze in van de invoer van het formulier‑check‑box.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Haalt de aangevinkte waarde op of stelt deze in van de invoer van het formulier‑check‑box.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | handtekening | java.lang.Object | Handtekeningobject om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven handtekeningobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Handtekening hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloon FormField Signature‑instantie.


**Returns:**
java.lang.Object - Retourneert gekloonde FormField Signature‑instantie.

