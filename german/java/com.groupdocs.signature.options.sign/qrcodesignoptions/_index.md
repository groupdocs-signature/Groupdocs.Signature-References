---
title: "QrCodeSignOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die QR-Code-Signaturoptionen dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

Stellt die QR-Code-Signaturoptionen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | Initialisiert eine neue Instanz der Klasse QRCodeSignOptions mit Standardwerten. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse QRCodeSignOptions mit Text. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Liest oder setzt den QRCode-Typ. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Liest oder setzt den QRCode-Typ. |
|
|  | [getForeColor()](#getForeColor--) | Liest oder setzt die Vordergrundfarbe der QR‑Code‑Balken |
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Liest oder setzt die Vordergrundfarbe der QR‑Code‑Balken |
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Liest oder setzt die Vordergrundfarbe der QR‑Code‑Balken |
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen.
|
|  | [getInnerMargins()](#getInnerMargins--) | Liest oder setzt den Abstand zwischen QRCode-Elementen und den Rändern des Ergebnisbildes. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Liest oder setzt den Abstand zwischen QRCode-Elementen und den Rändern des Ergebnisbildes. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Liest oder setzt die Ausrichtung des Textes im Ergebnis‑QR‑Code‑Bild. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Liest oder setzt die Ausrichtung des Textes im Ergebnis‑QR‑Code‑Bild. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | Liest oder setzt den Dateinamen des QR‑Code‑Logo‑Bildes. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | Liest oder setzt den Dateinamen des QR‑Code‑Logo‑Bildes. |
|
|  | [getLogoStream()](#getLogoStream--) | Liest oder setzt den Bildstrom des QR‑Code‑Logos. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | Liest oder setzt den Bildstrom des QR‑Code‑Logos. |
|
|  | [getData()](#getData--) | Liest oder setzt ein benutzerdefiniertes Objekt, das in QR‑Code‑Inhalt serialisiert wird. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | Liest oder setzt ein benutzerdefiniertes Objekt, das in QR‑Code‑Inhalt serialisiert wird. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften. |
|
|  | [getReturnContent()](#getReturnContent--) | Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentseite platziert wurde. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentseite platziert wurde. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
|
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


Initialisiert eine neue Instanz der Klasse QRCodeSignOptions mit Standardwerten.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


Initialisiert eine neue Instanz der Klasse QRCodeSignOptions mit Text.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | Signaturtext. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Text | java.lang.String | QRCode‑Text |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode‑Kodierungstyp siehe [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Liest oder setzt den QRCode-Typ.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Liest oder setzt den QRCode-Typ.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Liest oder setzt die Vordergrundfarbe der QR‑Code‑Balken
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Liest oder setzt die Vordergrundfarbe der QR‑Code‑Balken
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Liest oder setzt die Vordergrundfarbe der QR‑Code‑Balken
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Liest oder setzt den Abstand zwischen QRCode-Elementen und den Rändern des Ergebnisbildes.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Liest oder setzt den Abstand zwischen QRCode-Elementen und den Rändern des Ergebnisbildes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Liest oder setzt die Ausrichtung des Textes im Ergebnis‑QR‑Code‑Bild.
Standardwert ist None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Liest oder setzt die Ausrichtung des Textes im Ergebnis‑QR‑Code‑Bild.
Standardwert ist None.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


Liest oder setzt den Dateinamen des QR‑Code‑Logo‑Bildes.
Diese Eigenschaft wird nur verwendet, wenn LogoStream nicht angegeben ist.
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


Liest oder setzt den Dateinamen des QR‑Code‑Logo‑Bildes.
Diese Eigenschaft wird nur verwendet, wenn LogoStream nicht angegeben ist.
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


Liest oder setzt den Bildstrom des QR‑Code‑Logos.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von LogoGuid verwendet.
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


Liest oder setzt den Bildstrom des QR‑Code‑Logos.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von LogoGuid verwendet.
Die Verwendung dieser Eigenschaft kann zu Problemen bei der Verifizierung führen. Verwenden Sie sie vorsichtig.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


Liest oder setzt ein benutzerdefiniertes Objekt, das in QR‑Code‑Inhalt serialisiert wird.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


Liest oder setzt ein benutzerdefiniertes Objekt, das in QR‑Code‑Inhalt serialisiert wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentseite platziert wurde.
Wenn dieses Flag auf true gesetzt ist, behält der QR-Code‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format bei.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Standardmäßig ist diese Option deaktiviert.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt einer Signatur abzurufen, die auf einer Dokumentseite platziert wurde.
Wenn dieses Flag auf true gesetzt ist, behält der QR-Code‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format bei.
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


Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist.
Standardmäßig ist es auf Null gesetzt. Das bedeutet, dass der QR-Code‑Bildinhalt im Originalformat zurückgegeben wird.
Dieses Bildformat ist angegeben bei
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP.
Wenn das angegebene Format nicht unterstützt wird, wird der QR-Code‑Bildinhalt im .png‑Format zurückgegeben.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist.
Standardmäßig ist es auf Null gesetzt. Das bedeutet, dass der QR-Code‑Bildinhalt im Originalformat zurückgegeben wird.
Dieses Bildformat ist angegeben bei
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP.
Wenn das angegebene Format nicht unterstützt wird, wird der QR-Code‑Bildinhalt im .png‑Format zurückgegeben.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
