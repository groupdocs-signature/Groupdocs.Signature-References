---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen voor een keuzelijst invoerveldhandtekening."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Bevat eigenschappen voor een keuzelijst invoerveldhandtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Maakt ComboboxFormFieldSignature aan met een vooraf gedefinieerde naam. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Maakt ComboboxFormFieldSignature aan met een vooraf gedefinieerde naam en optielijst. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Maakt ComboboxFormFieldSignature aan met een vooraf gedefinieerde naam, optielijst en geselecteerde waarde. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSelected()](#getSelected--) | Haal de geselecteerde waarde op of stel deze in. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Haal de geselecteerde waarde op of stel deze in. |
|
|  | [getItems()](#getItems--) | Haal de optielijst van de combo‑box op of stel deze in. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Haal de optielijst van de combo‑box op of stel deze in. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon FormField Signature‑instantie. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Maakt ComboboxFormFieldSignature aan met een vooraf gedefinieerde naam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Maakt ComboboxFormFieldSignature aan met een vooraf gedefinieerde naam en optielijst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|
|  | items | java.util.List<java.lang.String> | Waarden van de combo‑boxlijst. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Maakt ComboboxFormFieldSignature aan met een vooraf gedefinieerde naam, optielijst en geselecteerde waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | name | java.lang.String | Naam van het formulier‑veldobject. |
|
|  | items | java.util.List<java.lang.String> | Waarden van de combo‑boxlijst. |
|
|  | selected | java.lang.Object | Geselecteerde waarde. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Haal de geselecteerde waarde op of stel deze in.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Haal de geselecteerde waarde op of stel deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Haal de optielijst van de combo‑box op of stel deze in.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Haal de optielijst van de combo‑box op of stel deze in.


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

