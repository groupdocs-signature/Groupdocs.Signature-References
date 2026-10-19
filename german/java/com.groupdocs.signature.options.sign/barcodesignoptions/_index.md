---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die Barcode-Signaturoptionen dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Stellt die Barcode-Signaturoptionen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Standardwerten. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Liest oder setzt den Barcode-Typ. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Liest oder setzt den Barcode-Typ. |
|
|  | [getForeColor()](#getForeColor--) | Liest oder setzt die Vordergrundfarbe der Barcode-Streifen |
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Liest oder setzt die Vordergrundfarbe der Barcode-Streifen |
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Liest oder setzt die Vordergrundfarbe der Barcode-Streifen |
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen.
|
|  | [getInnerMargins()](#getInnerMargins--) | Liest oder setzt den Abstand zwischen Barcode-Elementen und den Rändern des Ergebnisbildes. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Liest oder setzt den Abstand zwischen Barcode-Elementen und den Rändern des Ergebnisbildes. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Liest oder setzt die Ausrichtung des Textes im Ergebnis‑Barcode‑Bild. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Liest oder setzt die Ausrichtung des Textes im Ergebnis‑Barcode‑Bild. |
|
|  | [getReturnContent()](#getReturnContent--) | Liest oder setzt das Flag, um den Barcode‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentenseite platziert wurde. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Liest oder setzt das Flag, um den Barcode‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentenseite platziert wurde. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die Eigenschaft ReturnContent aktiviert ist. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die Eigenschaft ReturnContent aktiviert ist. |
|
|  | [validate()](#validate--) | Interne Methode zur Validierung der Barcode‑Optionen‑Parameter. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Standardwerten.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Barcode-Text |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Barcode-Text |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode‑Kodierungstyp siehe [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Liest oder setzt den Barcode-Typ.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Liest oder setzt den Barcode-Typ.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Liest oder setzt die Vordergrundfarbe der Barcode-Streifen
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Liest oder setzt die Vordergrundfarbe der Barcode-Streifen
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Liest oder setzt die Vordergrundfarbe der Barcode-Streifen
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Liest oder setzt den Abstand zwischen Barcode-Elementen und den Rändern des Ergebnisbildes.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Liest oder setzt den Abstand zwischen Barcode-Elementen und den Rändern des Ergebnisbildes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Liest oder setzt die Ausrichtung des Textes im Ergebnis‑Barcode‑Bild.
Standardwert ist None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Liest oder setzt die Ausrichtung des Textes im Ergebnis‑Barcode‑Bild.
Standardwert ist None.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Liest oder setzt das Flag, um den Barcode‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentenseite platziert wurde.
Wenn dieses Flag auf true gesetzt ist, behält der Bildinhalt der Barcode‑Signatur die Rohbilddaten im erforderlichen Format bei.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standardmäßig ist diese Option deaktiviert.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Liest oder setzt das Flag, um den Barcode‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentenseite platziert wurde.
Wenn dieses Flag auf true gesetzt ist, behält der Bildinhalt der Barcode‑Signatur die Rohbilddaten im erforderlichen Format bei.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standardmäßig ist diese Option deaktiviert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die Eigenschaft ReturnContent aktiviert ist.
Standardmäßig ist sie auf Null gesetzt. Das bedeutet, dass der Barcode‑Bildinhalt im Originalformat zurückgegeben wird.
Dieses Bildformat ist angegeben bei
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP.
Wenn das angegebene Format nicht unterstützt wird, wird der Barcode‑Bildinhalt im .png‑Format zurückgegeben.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der Barcode‑Signatur an, wenn die Eigenschaft ReturnContent aktiviert ist.
Standardmäßig ist sie auf Null gesetzt. Das bedeutet, dass der Barcode‑Bildinhalt im Originalformat zurückgegeben wird.
Dieses Bildformat ist angegeben bei
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP.
Wenn das angegebene Format nicht unterstützt wird, wird der Barcode‑Bildinhalt im .png‑Format zurückgegeben.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Interne Methode zur Validierung der Barcode‑Optionen‑Parameter.


### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
