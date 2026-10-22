---
title: "BarcodeSearchOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt abstrakte Suchoptionen für Barcode‑Signaturen dar."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Stellt abstrakte Suchoptionen für Barcode‑Signaturen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Initialisiert eine neue Instanz der Klasse SearchBarcodeOptions mit Standardwerten. |
| [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initialisiert eine neue Instanz der Klasse SearchBarcodeOptions mit dem Encode‑Typ‑Wert. |
| [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse SearchBarcodeOptions mit Encode‑Typ‑ und Textwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gibt die Encode‑Type‑Eigenschaft zum Suchen von Barcodes an. |
| [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Gibt die Encode‑Type‑Eigenschaft zum Suchen von Barcodes an. |
| [getText()](#getText--) | Gibt den Text der Barcode‑Signatur an, wenn er gesucht und abgeglichen werden soll. |
| [setText(String value)](#setText-java.lang.String-) | Gibt den Text der Barcode‑Signatur an, wenn er gesucht und abgeglichen werden soll. |
| [getMatchType()](#getMatchType--) | Liest oder setzt die Barcode‑Text‑Match‑Type‑Suche. |
| [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt die Barcode‑Text‑Match‑Type‑Suche. |
| [getReturnContent()](#getReturnContent--) | Liest oder setzt das Flag, um den Barcode‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Liest oder setzt das Flag, um den Barcode‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. |
| [getReturnContentType()](#getReturnContentType--) | Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Initialisiert eine neue Instanz der Klasse SearchBarcodeOptions mit Standardwerten.

### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Initialisiert eine neue Instanz der Klasse SearchBarcodeOptions mit dem Encode‑Typ‑Wert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Gibt den Barcode‑Encode‑Typ an. |

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Initialisiert eine neue Instanz der Klasse SearchBarcodeOptions mit Encode‑Typ‑ und Textwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Gibt den Barcode‑Encode‑Typ an. |
| text | java.lang.String | Setzt den Text der Barcode‑Signatur. |

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Gibt die Encode‑Type‑Eigenschaft zum Suchen von Barcodes an. Wenn dieser Wert nicht gesetzt ist, wird die Suche für alle unterstützten Barcode‑Typen durchgeführt.

**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Gibt die Encode‑Type‑Eigenschaft zum Suchen von Barcodes an. Wenn dieser Wert nicht gesetzt ist, wird die Suche für alle unterstützten Barcode‑Typen durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Gibt den Text der Barcode‑Signatur an, wenn er gesucht und abgeglichen werden soll.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gibt den Text der Barcode‑Signatur an, wenn er gesucht und abgeglichen werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Liest oder setzt die Barcode‑Text‑Match‑Type‑Suche. Sie wird nur verwendet, wenn die Text‑Eigenschaft gesetzt ist.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Liest oder setzt die Barcode‑Text‑Match‑Type‑Suche. Sie wird nur verwendet, wenn die Text‑Eigenschaft gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Liest oder setzt das Flag, um den Barcode‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. Wenn dieses Flag auf true gesetzt ist, behält der Barcode‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)). Standardmäßig ist diese Option deaktiviert.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Liest oder setzt das Flag, um den Barcode‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. Wenn dieses Flag auf true gesetzt ist, behält der Barcode‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)). Standardmäßig ist diese Option deaktiviert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der Barcode‑Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei BarcodeSignature.Format angegeben ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}). Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der Barcode‑Bildinhalt im .png‑Format zurückgegeben.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der Barcode‑Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei BarcodeSignature.Format angegeben ([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature\#getFormat)\}). Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der Barcode‑Bildinhalt im .png‑Format zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

