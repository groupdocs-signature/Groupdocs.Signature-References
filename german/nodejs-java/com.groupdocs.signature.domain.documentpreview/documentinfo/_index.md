---
title: "DocumentInfo"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Definiert Eigenschaften der Dokumentenbeschreibung."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definiert Eigenschaften der Dokumentenbeschreibung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | Initialisiert eine neue Instanz der [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageCount()](#getPageCount--) | Anzahl der Dokumentseiten. |
| [setPageCount(int value)](#setPageCount-int-) | Anzahl der Dokumentseiten. |
| [getPages()](#getPages--) | Sammlung von Beschreibungen der Dokumentseiten. |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Sammlung von Beschreibungen der Dokumentseiten. |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Gibt die Breite für die maximale Seitenhöhe an. |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Gibt die Breite für die maximale Seitenhöhe an. |
| [getMaxPageHeight()](#getMaxPageHeight--) | Gibt die maximale Seitenhöhe an. |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Gibt die maximale Seitenhöhe an. |
| [getFileType()](#getFileType--) | Dateiformattyp. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Dateiformattyp. |
| [getSize()](#getSize--) | Dokumentgröße in Bytes. |
| [setSize(long value)](#setSize-long-) | Dokumentgröße in Bytes. |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | Sammlung von Textsignaturen des Dokuments. |
| [getImageSignatures()](#getImageSignatures--) | Sammlung von Bildsignaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Sammlung von digitalen Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden. |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | Sammlung von Barcode‑Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden. |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | Sammlung von QR‑Code‑Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden. |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | Sammlung von Form‑Feld‑Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden. |
| [getFormFields()](#getFormFields--) | Sammlung aller vorhandenen unterstützten Formfelder im Dokument. |
| [getMetadataSignatures()](#getMetadataSignatures--) | Sammlung von Metadaten‑Signaturen des Dokuments. |
| [getProcessLogs()](#getProcessLogs--) | Sammlung von Dokument‑Verlaufsprozessen wie Signieren, Aktualisieren, Löschen. |
| [getSignatures()](#getSignatures--) | Sammlung aller Signaturtypen des Dokuments [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Initialisiert eine neue Instanz der [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo)-Klasse.

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Anzahl der Dokumentseiten.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Anzahl der Dokumentseiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Sammlung von Beschreibungen der Dokumentseiten.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Sammlung von Beschreibungen der Dokumentseiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Gibt die Breite für die maximale Seitenhöhe an.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Gibt die Breite für die maximale Seitenhöhe an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Gibt die maximale Seitenhöhe an.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Gibt die maximale Seitenhöhe an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Dateiformattyp.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Dateiformattyp.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Dokumentgröße in Bytes.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Dokumentgröße in Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


Sammlung von Textsignaturen des Dokuments.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Sammlung von Bildsignaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Sammlung von digitalen Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Sammlung von Barcode‑Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Sammlung von QR‑Code‑Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Sammlung von Form‑Feld‑Signaturen des Dokuments, die durch [Signature](../../com.groupdocs.signature/signature)-Methoden hinzugefügt oder aktualisiert wurden.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Sammlung aller vorhandenen unterstützten Formularfelder im Dokument. Diese Eigenschaft wird nur für PDF- und Word‑Verarbeitungsdokumenttypen unterstützt.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Sammlung von Metadaten‑Signaturen des Dokuments.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Sammlung von Dokument‑Verlaufsprozessen wie Signieren, Aktualisieren, Löschen.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Sammlung aller Signaturtypen des Dokuments [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
