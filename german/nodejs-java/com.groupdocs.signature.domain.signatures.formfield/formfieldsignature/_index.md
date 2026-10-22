---
title: "FormFieldSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Eigenschaften für Form‑Feld‑Signaturen."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Enthält Eigenschaften für Form‑Feld‑Signaturen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Gibt eindeutigen Namen des Formularfelds an. |
| [setName(String value)](#setName-java.lang.String-) | Gibt eindeutigen Namen des Formularfelds an. |
| [getType()](#getType--) | Gibt den Typ des Formularfelds an. |
| [getValue()](#getValue--) | Gibt das Datenobjekt des Formularfelds an. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gibt das Datenobjekt des Formularfelds an. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die FormField Signature-Instanz. |
### getName() {#getName--}
```
public final String getName()
```


Gibt eindeutigen Namen des Formularfelds an.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gibt eindeutigen Namen des Formularfelds an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Gibt den Typ des Formularfelds an.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Gibt das Datenobjekt des Formularfelds an.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Gibt das Datenobjekt des Formularfelds an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

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
