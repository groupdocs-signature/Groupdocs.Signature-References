---
title: "QrCodeSearchOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt abstrakte Suchoptionen für QR‑Code‑Signaturen dar."
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.signature.options.search/qrcodesearchoptions/
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
| [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten. |
| [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit dem Wert des Kodierungstyps. |
| [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Kodierungstyp‑ und Textwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEncodeType()](#getEncodeType--) | Gibt die Eigenschaft Encode Type an, um QR‑Codes zu durchsuchen. |
| [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Gibt die Eigenschaft Encode Type an, um QR‑Codes zu durchsuchen. |
| [getText()](#getText--) | Gibt den QR‑Code‑Signaturtext an, falls er gesucht und abgeglichen werden soll. |
| [setText(String value)](#setText-java.lang.String-) | Gibt den QR‑Code‑Signaturtext an, falls er gesucht und abgeglichen werden soll. |
| [getMatchType()](#getMatchType--) | Liest oder setzt den Suchtyp für die QR‑Code‑Textübereinstimmung. |
| [setMatchType(int value)](#setMatchType-int-) | Liest oder setzt den Suchtyp für die QR‑Code‑Textübereinstimmung. |
| [getDataEncryption()](#getDataEncryption--) | Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest. |
| [getReturnContent()](#getReturnContent--) | Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. |
| [getReturnContentType()](#getReturnContentType--) | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR-Code-Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Gibt den Dateityp des zurückgegebenen Bildinhalts der QR-Code-Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. |
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten.

### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit dem Wert des Kodierungstyps.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Gibt den QR‑Code‑Kodierungstyp an. |

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Kodierungstyp‑ und Textwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Gibt den QR‑Code‑Kodierungstyp an. |
| text | java.lang.String | Setzt den Text der QR‑Code‑Signatur. |

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Gibt die Eigenschaft Encode Type an, um QR‑Codes zu durchsuchen. Wenn dieser Wert nicht gesetzt ist, wird die Suche für alle unterstützten QR‑Code‑Typen durchgeführt.

**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Gibt die Eigenschaft Encode Type an, um QR‑Codes zu durchsuchen. Wenn dieser Wert nicht gesetzt ist, wird die Suche für alle unterstützten QR‑Code‑Typen durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Gibt den QR‑Code‑Signaturtext an, falls er gesucht und abgeglichen werden soll.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Gibt den QR‑Code‑Signaturtext an, falls er gesucht und abgeglichen werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Liest oder setzt den Suchtyp für die QR‑Code‑Textübereinstimmung. Er wird nur verwendet, wenn die Eigenschaft Text gesetzt ist.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Liest oder setzt den Suchtyp für die QR‑Code‑Textübereinstimmung. Er wird nur verwendet, wenn die Eigenschaft Text gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ruft die Implementierung des [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) Interfaces zum Codieren und Decodieren von QR-Code-Signatur-Text- oder Daten-Eigenschaften ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. Wenn dieses Flag auf true gesetzt ist, behält der QR‑Code‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)). Standardmäßig ist diese Option deaktiviert.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Liest oder setzt das Flag, um den QR‑Code‑Bildinhalt der Signatur auf der Dokumentseite zu erfassen. Wenn dieses Flag auf true gesetzt ist, behält der QR‑Code‑Signatur‑Bildinhalt die Rohbilddaten im erforderlichen Format ReturnContentType (\\#getReturnContentType.getReturnContentType/\\#setReturnContentType(FileType).setReturnContentType(FileType)). Standardmäßig ist diese Option deaktiviert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der QR-Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der QR-Code‑Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei QrCodeSignature.Format () angegeben. Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der QR-Code‑Bildinhalt im ursprünglichen .png zurückgegeben.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Gibt den Dateityp des zurückgegebenen Bildinhalts der QR-Code‑Signatur an, wenn die ReturnContent‑Eigenschaft aktiviert ist. Standardmäßig ist er auf Null gesetzt. Das bedeutet, dass der QR-Code‑Bildinhalt im Originalformat zurückgegeben wird. Dieses Bildformat wird bei QrCodeSignature.Format () angegeben. Mögliche unterstützte Werte sind: FileType.JPEG, FileType.PNG, FileType.BMP. Wenn das angegebene Format nicht unterstützt wird, wird der QR-Code‑Bildinhalt im ursprünglichen .png zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

