---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för combo-box inmatningsformulärsignatur."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Innehåller egenskaper för combo-box inmatningsformulärsignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Skapar ComboboxFormFieldSignature med fördefinierat namn. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Skapar ComboboxFormFieldSignature med fördefinierat namn och alternativlista. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Skapar ComboboxFormFieldSignature med fördefinierat namn, alternativlista och valt värde. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSelected()](#getSelected--) | Hämta eller ange valt värde. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Hämta eller ange valt värde. |
|
|  | [getItems()](#getItems--) | Hämta eller ange alternativlista för kombinationsrutan. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Hämta eller ange alternativlista för kombinationsrutan. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona FormField Signature-instans. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Skapar ComboboxFormFieldSignature med fördefinierat namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Skapar ComboboxFormFieldSignature med fördefinierat namn och alternativlista.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|
|  | items | java.util.List<java.lang.String> | Värden i listan för kombinationsrutan. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Skapar ComboboxFormFieldSignature med fördefinierat namn, alternativlista och valt värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på formulärfältobjekt. |
|
|  | items | java.util.List<java.lang.String> | Värden i listan för kombinationsrutan. |
|
|  | vald | java.lang.Object | Valt värde. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Hämta eller ange valt värde.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Hämta eller ange valt värde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Hämta eller ange alternativlista för kombinationsrutan.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Hämta eller ange alternativlista för kombinationsrutan.


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

