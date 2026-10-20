---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för check-box inmatningsformulärsignatur."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Innehåller egenskaper för check-box inmatningsformulärsignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Skapar PdfCheckboxFormFieldSignature med fördefinierat namn. |
|
|  | [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Skapar PdfCheckboxFormFieldSignature med fördefinierat namn och värde |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getChecked()](#getChecked--) | Hämtar eller anger markerat värde för formulärfältets kryssruta. |
|
|  | [setChecked(boolean value)](#setChecked-boolean-) | Hämtar eller anger markerat värde för formulärfältets kryssruta. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona FormField Signature-instans. |
|
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Skapar PdfCheckboxFormFieldSignature med fördefinierat namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Skapar PdfCheckboxFormFieldSignature med fördefinierat namn och värde


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|
|  | isChecked | boolean | Värde om kryssrutan är markerad |
|

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Hämtar eller anger markerat värde för formulärfältets kryssruta.


**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Hämtar eller anger markerat värde för formulärfältets kryssruta.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Skriver över Equals-metoden för att jämföra signaturens egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatur | java.lang.Object | Signaturobjekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda signaturobjektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Signaturens hashkod

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klona FormField Signature-instans.


**Returns:**
java.lang.Object – Returnerar klonad FormField Signature-instans.

