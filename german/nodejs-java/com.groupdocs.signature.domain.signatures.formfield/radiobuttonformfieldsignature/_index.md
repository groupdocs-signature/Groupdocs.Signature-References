---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld Radio‑Button‑Signatur."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld Radio‑Button‑Signatur.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Erstellt RadioButtonFieldSignature mit vordefiniertem Namen. |
| [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Erstellt RadioButtonFieldSignature mit vordefiniertem Namen und Elementliste. |
| [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Erstellt RadioButtonFieldSignature mit vordefiniertem Namen, Elementliste und ausgewähltem Wert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelected()](#getSelected--) | Enthält ausgewählten Wert. |
| [setSelected(String value)](#setSelected-java.lang.String-) | Enthält ausgewählten Wert. |
| [getItems()](#getItems--) | Lese oder setze Optionsliste der Radio-Buttons. |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Lese oder setze Optionsliste der Radio-Buttons. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die FormField Signature-Instanz. |
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Erstellt RadioButtonFieldSignature mit vordefiniertem Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Erstellt RadioButtonFieldSignature mit vordefiniertem Namen und Elementliste.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |
| Elemente | java.util.List<java.lang.String> | Werte der Radio-Button-Liste. |

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Erstellt RadioButtonFieldSignature mit vordefiniertem Namen, Elementliste und ausgewähltem Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |
| Elemente | java.util.List<java.lang.String> | Werte der Radio-Button-Liste. |
| ausgewählt | java.lang.Object | Ausgewählter Wert. |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Enthält ausgewählten Wert.

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Enthält ausgewählten Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Lese oder setze Optionsliste der Radio-Buttons.

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Lese oder setze Optionsliste der Radio-Buttons.

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
