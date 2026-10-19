---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld Text‑Signatur für PDF‑Dokument."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld Text‑Signatur für PDF‑Dokument.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getText()](#getText--) | Liest oder setzt den Text des Form‑Feld‑Texteingabefelds. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Text des Form‑Feld‑Texteingabefelds. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Klonen Sie die FormField Signature-Instanz. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Formularfeld-Objekts. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Name | java.lang.String | Name des Formularfeld-Objekts. |
|
|  | Text | java.lang.String | Text des Formularfeldobjekts. |
|

### getText() {#getText--}
```
public final String getText()
```


Liest oder setzt den Text des Form‑Feld‑Texteingabefelds.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Liest oder setzt den Text des Form‑Feld‑Texteingabefelds.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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

