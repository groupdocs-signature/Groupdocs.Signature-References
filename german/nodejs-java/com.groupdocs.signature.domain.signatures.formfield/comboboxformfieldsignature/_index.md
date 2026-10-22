---
title: "ComboboxFormFieldSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld Combo‑Box‑Signatur."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld Combo‑Box‑Signatur.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen. |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen und Optionsliste. |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen, Optionsliste und ausgewähltem Wert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelected()](#getSelected--) | Liest oder legt den ausgewählten Wert fest. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Liest oder legt den ausgewählten Wert fest. |
| [getItems()](#getItems--) | Liest oder legt die Optionsliste des Kombinationsfeldes fest. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Liest oder legt die Optionsliste des Kombinationsfeldes fest. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die FormField Signature-Instanz. |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen und Optionsliste.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |
| Elemente | java.util.List<java.lang.String> | Werte der Kombinationsfeldliste. |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Erstellt ComboboxFormFieldSignature mit vordefiniertem Namen, Optionsliste und ausgewähltem Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |
| Elemente | java.util.List<java.lang.String> | Werte der Kombinationsfeldliste. |
| ausgewählt | java.lang.Object | Ausgewählter Wert. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Liest oder legt den ausgewählten Wert fest.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Liest oder legt den ausgewählten Wert fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Liest oder legt die Optionsliste des Kombinationsfeldes fest.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Liest oder legt die Optionsliste des Kombinationsfeldes fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<java.lang.String> |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | java.lang.Object | Signatur-Objekt zum Vergleichen. |

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signatur-Objekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.
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


Klont die FormField Signature-Instanz.

**Returns:**
java.lang.Object - Gibt die geklonte FormField Signature-Instanz zurück.
