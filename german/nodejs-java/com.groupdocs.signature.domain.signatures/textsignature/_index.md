---
title: "TextSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Textsignatur‑Eigenschaften."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Enthält Textsignatur‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Initialisiere das TextSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. |
| [TextSignature()](#TextSignature--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Gibt den Text in der Signatur an. |
| [setText(String value)](#setText-java.lang.String-) | Gibt den Text in der Signatur an. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Gibt die Implementierung der Textsignatur an. |
| [getNative()](#getNative--) | Gibt das native Attribut an. |
| [setNative(boolean value)](#setNative-boolean-) | Gibt das native Attribut an. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klonen Sie die Textsignatur-Instanz. |
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Initialisiere das TextSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. Dieser eindeutige Identifikator wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Dokumenten-Signatur-Informationsschicht zu finden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | java.lang.String | Eindeutiger Signatur-Identifikator, der durch Signatur- oder Suchmethode erhalten wurde. |

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Gibt den Text in der Signatur an.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gibt den Text in der Signatur an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Gibt die Implementierung der Textsignatur an.

**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Gibt das native Attribut an. Es ist true, wenn die Signatur dokumentspezifisch ist.

**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Gibt das native Attribut an. Es ist true, wenn die Signatur dokumentspezifisch ist.

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


Klonen Sie die Textsignatur-Instanz.

**Returns:**
java.lang.Object - Gibt eine geklonte Textsignatur-Instanz zurück.
