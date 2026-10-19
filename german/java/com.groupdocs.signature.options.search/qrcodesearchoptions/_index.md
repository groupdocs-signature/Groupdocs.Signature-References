---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt abstrakte Suchoptionen für QR‑Code‑Signaturen dar."
type: docs
weight: 16
url: /de/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Stellt abstrakte Suchoptionen für QR‑Code‑Signaturen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit einem Kodierungstypwert. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Kodierungstyp‑ und Textwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Gibt die Encode Type‑Eigenschaft an, um QR‑Codes zu suchen. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Gibt die Encode Type‑Eigenschaft an, um QR‑Codes zu suchen. |
|
|  | [getText()](#getText--) | Gibt den QR‑Code‑Signaturtext an, wenn er gesucht und abgeglichen werden soll. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Gibt den QR‑Code‑Signaturtext an, wenn er gesucht und abgeglichen werden soll. |
|
|  | [getMatchType()](#getMatchType--) | Liest oder setzt die QR‑Code‑Text‑Übereinstimmungstyp‑Suche. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt die QR‑Code‑Text‑Übereinstimmungstyp‑Suche. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Liest oder setzt die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)-Interfaces zum Kodieren und Dekodieren von QR‑Code‑Signaturtext‑ oder Dateneigenschaften. |
|
|  | [getReturnContent()](#getReturnContent--) | Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentenseite zu erfassen. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentenseite zu erfassen. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR‑Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit einem Kodierungstypwert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Gibt den QR‑Code‑Encode‑Typ an. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Kodierungstyp‑ und Textwerten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Gibt den QR‑Code‑Encode‑Typ an. |
|
|  | Text | java.lang.String | Setzt den Text der QR‑Code‑Signatur. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Gibt die Encode Type‑Eigenschaft an, um QR‑Codes zu suchen.
Wenn dieser Wert nicht gesetzt ist, wird die Suche für alle unterstützten QR‑Code‑Typen durchgeführt.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Gibt die Encode Type‑Eigenschaft an, um QR‑Codes zu suchen.
Wenn dieser Wert nicht gesetzt ist, wird die Suche für alle unterstützten QR‑Code‑Typen durchgeführt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Gibt den QR‑Code‑Signaturtext an, wenn er gesucht und abgeglichen werden soll.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gibt den QR‑Code‑Signaturtext an, wenn er gesucht und abgeglichen werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Liest oder setzt die QR‑Code‑Text‑Übereinstimmungstyp‑Suche. Sie wird nur verwendet, wenn die Text‑Eigenschaft gesetzt ist.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Liest oder setzt die QR‑Code‑Text‑Übereinstimmungstyp‑Suche. Sie wird nur verwendet, wenn die Text‑Eigenschaft gesetzt ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

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


Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentenseite zu erfassen.
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


Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentenseite zu erfassen.
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
()
Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP.
Wenn das angegebene Format nicht unterstützt wird, wird der QR‑Code‑Bildinhalt im ursprünglichen .png zurückgegeben.


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
()
Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP.
Wenn das angegebene Format nicht unterstützt wird, wird der QR‑Code‑Bildinhalt im ursprünglichen .png zurückgegeben.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

