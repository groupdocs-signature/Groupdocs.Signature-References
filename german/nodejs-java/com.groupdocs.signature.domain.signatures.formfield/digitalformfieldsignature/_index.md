---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften für das Eingabeformularfeld Digitale Signatur für Pdf‑Dokumente."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Enthält Eigenschaften für das Eingabeformularfeld Digitale Signatur für Pdf‑Dokumente.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | Erstellt PdfDigitalFormFieldSignature mit vordefiniertem Namen. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSigned()](#getSigned--) | Nur-Lese-Eigenschaft, die anzeigt, ob die Form-field Signature mit einem digitalen Zertifikat signiert wurde. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die FormField Signature-Instanz. |
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


Erstellt PdfDigitalFormFieldSignature mit vordefiniertem Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | Name des Formularfeld-Objekts. |

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


Nur-Lese-Eigenschaft, die anzeigt, ob die Form-field Signature mit einem digitalen Zertifikat signiert wurde.

**Returns:**
boolean
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
