---
title: "CheckboxFormFieldSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld Check‑Box‑Signatur."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld Check‑Box‑Signatur.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | Erstellt PdfCheckboxFormFieldSignature mit vordefiniertem Namen. |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | Erstellt PdfCheckboxFormFieldSignature mit vordefiniertem Namen und Wert. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChecked()](#getChecked--) | Liest oder legt den aktivierten Wert des Formularfeld-Checkbox-Eingabefeldes fest. |
| [setChecked(boolean value)](#setChecked-boolean-) | Liest oder legt den aktivierten Wert des Formularfeld-Checkbox-Eingabefeldes fest. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die FormField Signature-Instanz. |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


Erstellt PdfCheckboxFormFieldSignature mit vordefiniertem Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


Erstellt PdfCheckboxFormFieldSignature mit vordefiniertem Namen und Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |
| isChecked | boolean | Wert, wenn die Checkbox aktiviert ist. |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


Liest oder legt den aktivierten Wert des Formularfeld-Checkbox-Eingabefeldes fest.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


Liest oder legt den aktivierten Wert des Formularfeld-Checkbox-Eingabefeldes fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
