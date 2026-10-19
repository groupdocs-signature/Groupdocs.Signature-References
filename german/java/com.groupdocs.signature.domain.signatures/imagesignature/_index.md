---
title: "ImageSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Bildsignatur-Eigenschaften."
type: docs
weight: 14
url: /de/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Enthält Bildsignatur-Eigenschaften.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Initialisiert das ImageSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. |
|
|  | [ImageSignature()](#ImageSignature--) | Initialisiert ImageSignature mit Standardparametern. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSize()](#getSize--) | Gibt die Größe des Signaturbildes in Bytes an. |
|
|  | [setSize(int value)](#setSize-int-) | Gibt die Größe des Signaturbildes in Bytes an. |
|
|  | [getFormat()](#getFormat--) | Gibt das Format des Signaturbildes an. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt das Format des Signaturbildes an. |
|
|  | [getContent()](#getContent--) | Gibt den Binärdateninhalt des Bildes vom Typ an |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Barcode-Signaturinstanz klonen. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Initialisiert das ImageSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde.
Dieser eindeutige Bezeichner wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Signatur‑Informationsebene des Dokuments zu finden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureId | java.lang.String | Einzigartige Signatur-Identifikationsnummer, die durch die Sign- oder Search-Methode der Signature-Klasse [Signature](../../com.groupdocs.signature/signature) erhalten wird. |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Initialisiert ImageSignature mit Standardparametern.


### getSize() {#getSize--}
```
public final int getSize()
```


Gibt die Größe des Signaturbildes in Bytes an.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Gibt die Größe des Signaturbildes in Bytes an.



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


Gibt den Binärdateninhalt des Bildes vom Typ an
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Standardmäßig wird diese Eigenschaft nicht gesetzt.
Eigenschaft verwenden
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) um diese Funktion zu aktivieren.


**Returns:**
byte[]
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


Barcode-Signaturinstanz klonen.


**Returns:**
java.lang.Object - Gibt eine geklonte Barcode‑Signaturinstanz zurück.

