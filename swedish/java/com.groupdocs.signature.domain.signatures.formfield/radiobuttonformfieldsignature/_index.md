---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för radio-button inmatningsformulärsignatur."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Innehåller egenskaper för radio-button inmatningsformulärsignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Skapar RadioButtonFieldSignature med fördefinierat namn. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Skapar RadioButtonFieldSignature med fördefinierat namn och objektlista. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Skapar RadioButtonFieldSignature med fördefinierat namn, objektlista och valt värde. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSelected()](#getSelected--) | Innehåller valt värde. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Innehåller valt värde. |
|
|  | [getItems()](#getItems--) | Hämta eller ange alternativlista för radioknappar. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Hämta eller ange alternativlista för radioknappar. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona FormField Signature-instans. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Skapar RadioButtonFieldSignature med fördefinierat namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Skapar RadioButtonFieldSignature med fördefinierat namn och objektlista.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|
|  | items | java.util.List<java.lang.String> | Värden för radioknappslista. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Skapar RadioButtonFieldSignature med fördefinierat namn, objektlista och valt värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|
|  | items | java.util.List<java.lang.String> | Värden för radioknappslista. |
|
|  | vald | java.lang.Object | Valt värde. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Innehåller valt värde.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Innehåller valt värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Hämta eller ange alternativlista för radioknappar.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Hämta eller ange alternativlista för radioknappar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<java.lang.String> |  |

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

