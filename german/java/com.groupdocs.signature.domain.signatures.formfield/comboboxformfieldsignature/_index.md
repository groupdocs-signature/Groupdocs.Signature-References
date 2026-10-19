---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld combo-box Signatur."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld combo-box Signatur.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen und Optionsliste. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen, Optionsliste und ausgewähltem Wert. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSelected()](#getSelected--) | Lese oder setze den ausgewählten Wert. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Lese oder setze den ausgewählten Wert. |
|
|  | [getItems()](#getItems--) | Lese oder setze die Optionsliste des Kombinationsfelds. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Lese oder setze die Optionsliste des Kombinationsfelds. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Klonen Sie die FormField Signature-Instanz. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Formularfeld-Objekts. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen und Optionsliste.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Formularfeld-Objekts. |
|
|  | Elemente | java.util.List<java.lang.String> | Werte der Kombinationsfeld‑Liste. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen, Optionsliste und ausgewähltem Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Formularfeld-Objekts. |
|
|  | Elemente | java.util.List<java.lang.String> | Werte der Kombinationsfeld‑Liste. |
|
|  | ausgewählt | java.lang.Object | Ausgewählter Wert. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Lese oder setze den ausgewählten Wert.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Lese oder setze den ausgewählten Wert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Lese oder setze die Optionsliste des Kombinationsfelds.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Lese oder setze die Optionsliste des Kombinationsfelds.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<java.lang.String> |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Signatur | java.lang.Object | Signaturobjekt zum Vergleich. |
|

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signaturobjekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode


**Returns:**
int - Signatur-Hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klonen Sie die FormField Signature-Instanz.


**Returns:**
java.lang.Object - Gibt eine geklonte FormField Signature-Instanz zurück.

