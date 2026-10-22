---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld Text‑Signatur für Pdf‑Dokument"
type: docs
weight: 15
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld Text‑Signatur für Pdf‑Dokument
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen. |
| [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Lese oder setze den Text des Formulareingabefelds. |
| [setText(String value)](#setText-java.lang.String-) | Lese oder setze den Text des Formulareingabefelds. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die FormField Signature-Instanz. |
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Erstellt PdfTextFormFieldSignature mit vordefiniertem Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |
| text | java.lang.String | Text des Formularfeldobjekts. |

### getText() {#getText--}
```
public final String getText()
```


Lese oder setze den Text des Formulareingabefelds.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Lese oder setze den Text des Formulareingabefelds.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
