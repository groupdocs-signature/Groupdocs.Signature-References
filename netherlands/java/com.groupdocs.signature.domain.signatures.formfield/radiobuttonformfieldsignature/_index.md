---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen voor een keuzerondje invoerveldhandtekening."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Bevat eigenschappen voor een keuzerondje invoerveldhandtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Maakt RadioButtonFieldSignature met vooraf gedefinieerde naam. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Maakt RadioButtonFieldSignature met vooraf gedefinieerde naam en itemslijst. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Maakt RadioButtonFieldSignature met vooraf gedefinieerde naam, itemslijst en geselecteerde waarde. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSelected()](#getSelected--) | Bevat geselecteerde waarde. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Bevat geselecteerde waarde. |
|
|  | [getItems()](#getItems--) | Haal of stel de optieslijst van radioknoppen in. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Haal of stel de optieslijst van radioknoppen in. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon FormField Signature‑instantie. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Maakt RadioButtonFieldSignature met vooraf gedefinieerde naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Maakt RadioButtonFieldSignature met vooraf gedefinieerde naam en itemslijst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|
|  | items | java.util.List<java.lang.String> | Waarden van radioknoplijst. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Maakt RadioButtonFieldSignature met vooraf gedefinieerde naam, itemslijst en geselecteerde waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|
|  | items | java.util.List<java.lang.String> | Waarden van radioknoplijst. |
|
|  | selected | java.lang.Object | Geselecteerde waarde. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Bevat geselecteerde waarde.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Bevat geselecteerde waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Haal of stel de optieslijst van radioknoppen in.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Haal of stel de optieslijst van radioknoppen in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<java.lang.String> |  |

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

