---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Barcode‑Signatur‑Eigenschaften."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Enthält Barcode‑Signatur‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Initialisiere das BarcodeSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. |
| [BarcodeSignature()](#BarcodeSignature--) | Initialisiere BarcodeSignature mit Standardparametern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gibt den Barcode‑Kodierungstyp an. |
| [getText()](#getText--) | Gibt den Text des Barcodes an. |
| [getFormat()](#getFormat--) | Gibt das Format des Barcode‑Signaturbildes an. |
| [getContent()](#getContent--) | Gibt den Binärdaten‑Bildinhalt des Barcodes vom Typ Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)) an. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die Barcode-Signatur-Instanz. |
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Initialisiere das BarcodeSignature-Objekt mit dem Signatur-Identifikator, der nach dem Suchvorgang erhalten wurde. Dieser eindeutige Identifikator wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Dokument‑Signatur‑Informationsebene zu finden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | java.lang.String | Einzigartiges Signaturkennzeichen, das durch die Sign- oder Search-Methode der Klasse Signature erhalten wurde [Signature](../../com.groupdocs.signature/signature). |

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Initialisiere BarcodeSignature mit Standardparametern.

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Gibt den Barcode‑Kodierungstyp an.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Gibt den Text des Barcodes an.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Gibt das Format des Barcode‑Signaturbildes an.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Gibt den Binärdaten‑Bildinhalt des Barcodes vom Typ Format (\#getFormat.getFormat/\#setFormat(FileType).setFormat(FileType)) an. Standardmäßig wird diese Eigenschaft nicht gesetzt. Verwende die Eigenschaft BarcodeSearchOptions.ReturnContent ([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions\#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions\#setReturnContent-boolean-)), um diese Funktion zu aktivieren.

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
### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| Bild | java.awt.image.BufferedImage |  |

