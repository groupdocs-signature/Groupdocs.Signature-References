---
title: "ImageSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Bildsignatur‑Eigenschaften."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Enthält Bildsignatur‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Initialisiert ein ImageSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. |
| [ImageSignature()](#ImageSignature--) | Initialisieren Sie ImageSignature mit Standardparametern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Gibt die Größe in Bytes des Signaturbildes an. |
| [setSize(int value)](#setSize-int-) | Gibt die Größe in Bytes des Signaturbildes an. |
| [getFormat()](#getFormat--) | Gibt das Format des Signaturbildes an. |
| [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt das Format des Signaturbildes an. |
| [getContent()](#getContent--) | Gibt den binären Bilddateninhalt vom Typ Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)) an. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die Barcode-Signatur-Instanz. |
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Initialisieren Sie das ImageSignature-Objekt mit dem Signaturkennzeichen, das nach dem Suchvorgang erhalten wurde. Dieses eindeutige Kennzeichen wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Signatur-Informationsschicht des Dokuments zu finden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | java.lang.String | Einzigartiges Signaturkennzeichen, das durch die Sign- oder Search-Methode der Klasse Signature erhalten wurde [Signature](../../com.groupdocs.signature/signature). |

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Initialisieren Sie ImageSignature mit Standardparametern.

### getSize() {#getSize--}
```
public final int getSize()
```


Gibt die Größe in Bytes des Signaturbildes an.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Gibt die Größe in Bytes des Signaturbildes an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Gibt das Format des Signaturbildes an.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Gibt das Format des Signaturbildes an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Gibt den binären Bilddateninhalt vom Typ Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)) an. Standardmäßig wird diese Eigenschaft nicht gesetzt. Verwenden Sie die Eigenschaft ImageSearchOptions.ReturnContent (\{ ImageSearchOptions\#getReturnContent\}/\{ ImageSearchOptions\#setReturnContent(boolean)\}), um diese Funktion zu aktivieren.

**Returns:**
byte[]
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


Klont die Barcode-Signatur-Instanz.

**Returns:**
java.lang.Object - Gibt eine geklonte Barcode-Signatur-Instanz zurück.
