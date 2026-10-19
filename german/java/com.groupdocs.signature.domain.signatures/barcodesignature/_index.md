---
title: "BarcodeSignature"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Enthält Barcode-Signatur-Eigenschaften."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Enthält Barcode-Signatur-Eigenschaften.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Initialisieren Sie das BarcodeSignature-Objekt mit der Signaturkennung, die nach dem Suchvorgang erhalten wurde. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | Initialisieren Sie BarcodeSignature mit Standardparametern. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Gibt den Barcode‑Kodierungstyp an. |
|
|  | [getText()](#getText--) | Gibt den Text des Barcodes an. |
|
|  | [getFormat()](#getFormat--) | Gibt das Format des Barcode‑Signaturbildes an. |
|
|  | [getContent()](#getContent--) | Gibt den Binärdaten‑Bildinhalt des Barcodes vom Typ an. |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode zum Vergleich von Signatur-Eigenschaften |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
|  | [deepClone()](#deepClone--) | Barcode-Signaturinstanz klonen. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Initialisieren Sie das BarcodeSignature-Objekt mit der Signaturkennung, die nach dem Suchvorgang erhalten wurde.
Dieser eindeutige Bezeichner wird verwendet, um zusätzliche Eigenschaften für diese Signatur aus der Signatur‑Informationsebene des Dokuments zu finden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | signatureId | java.lang.String | Einzigartige Signatur-Identifikationsnummer, die durch die Sign- oder Search-Methode der Signature-Klasse [Signature](../../com.groupdocs.signature/signature) erhalten wird. |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Initialisieren Sie BarcodeSignature mit Standardparametern.


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


Gibt den Binärdaten‑Bildinhalt des Barcodes vom Typ an.
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Standardmäßig wird diese Eigenschaft nicht gesetzt.
Eigenschaft verwenden
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) um diese Funktion zu aktivieren.


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

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| Bild | java.awt.image.BufferedImage |  |

