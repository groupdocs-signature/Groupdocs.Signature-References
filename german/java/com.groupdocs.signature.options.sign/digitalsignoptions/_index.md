---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die digitalen Signaturoptionen dar."
type: docs
weight: 11
url: /de/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Stellt die digitalen Signaturoptionen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit Standardwerten. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikats-Stream. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einer Bilddatei. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einem Bild-Stream. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikats-Stream und einer Bilddatei. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikats-Stream und einem Bild-Stream. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getReason()](#getReason--) | Liest oder setzt den Grund der Signatur. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Liest oder setzt den Grund der Signatur. |
|
|  | [getContact()](#getContact--) | Liest oder setzt den Signaturkontakt. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Liest oder setzt den Signaturkontakt. |
|
|  | [getLocation()](#getLocation--) | Liest oder setzt den Signaturort. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Liest oder setzt den Signaturort. |
|
|  | [getPassword()](#getPassword--) | Liest oder setzt das Passwort des digitalen Zertifikats. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das Passwort des digitalen Zertifikats. |
|
|  | [getSignature()](#getSignature--) | Liest oder setzt Eigenschaften der digitalen Dokumentensignatur. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Liest oder setzt Eigenschaften der digitalen Dokumentensignatur. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Liest oder setzt den Dateipfad des digitalen Zertifikats. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Liest oder setzt die GUID der digitalen Zertifikatsdatei. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Liest oder setzt den digitalen Zertifikats-Stream. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Liest oder setzt den digitalen Zertifikats-Stream. |
|
|  | [getVisible()](#getVisible--) | Liest oder setzt die Sichtbarkeit der Signatur. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Liest oder setzt die Sichtbarkeit der Signatur. |
|
|  | [getUseLtv()](#getUseLtv--) | Liest/setzt das LTV (Long Term Validation)-Validierungsflag. |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | Liest/setzt das LTV (Long Term Validation)-Validierungsflag. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | Liest oder setzt eine benutzerdefinierte Hash-Signatur-Implementierung, die es Aufrufern ermöglicht, ihre eigene |
Digitale Signaturlogik (HSM, Remote-Signer, Software-Keystore usw.).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | Setzt eine benutzerdefinierte Hash-Signatur-Implementierung, die es Aufrufern ermöglicht, ihre eigene |
Digitale Signaturlogik.
|
|  | [getXAdESType()](#getXAdESType--) | XAdES-Typ |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES-Typ |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | Überschreibe die String-Konvertierung. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit Standardwerten.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikats-Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitaler Zertifikat-Stream |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einer Bilddatei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
|
|  | imageFilePath | java.lang.String | Signaturdarstellung Bilddateipfad |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einem Bild-Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
|
|  | appearenceImageStream | java.io.InputStream | Signaturdarstellung Bild-Stream |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikats-Stream und einer Bilddatei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitaler Zertifikat-Stream |
|
|  | imageFilePath | java.lang.String | Signaturdarstellung Bilddateipfad |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikats-Stream und einem Bild-Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitaler Zertifikat-Stream |
|
|  | appearenceImageStream | java.io.InputStream | Signaturdarstellung Bild-Stream |
|

### getReason() {#getReason--}
```
public final String getReason()
```


Liest oder setzt den Grund der Signatur.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Liest oder setzt den Grund der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Liest oder setzt den Signaturkontakt.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Liest oder setzt den Signaturkontakt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Liest oder setzt den Signaturort.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Liest oder setzt den Signaturort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liest oder setzt das Passwort des digitalen Zertifikats.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Liest oder setzt das Passwort des digitalen Zertifikats.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Liest oder setzt Eigenschaften der digitalen Dokumentensignatur.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Liest oder setzt Eigenschaften der digitalen Dokumentensignatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Liest oder setzt den Dateipfad des digitalen Zertifikats.
Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Liest oder setzt die GUID der digitalen Zertifikatsdatei.
Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Liest oder setzt den digitalen Zertifikats-Stream.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateGuid verwendet.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Liest oder setzt den digitalen Zertifikats-Stream.
Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateGuid verwendet.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Liest oder setzt die Sichtbarkeit der Signatur.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Liest oder setzt die Sichtbarkeit der Signatur.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


Liest/setzt das LTV (Long Term Validation)-Validierungsflag.


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


Liest/setzt das LTV (Long Term Validation)-Validierungsflag.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


Liest oder setzt eine benutzerdefinierte Hash-Signatur-Implementierung, die es Aufrufern ermöglicht, ihre eigene
Digitale Signaturlogik (HSM, Remote-Signer, Software-Keystore usw.).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


Setzt eine benutzerdefinierte Hash-Signatur-Implementierung, die es Aufrufern ermöglicht, ihre eigene
Digitale Signaturlogik.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES-Typ
XAdESType
. Standardwert ist None (XAdES ist deaktiviert).
Derzeit wird der XAdES‑Signaturtyp nur für Tabellenkalkulationsdokumente unter .NET Framework unterstützt (nicht unter .NET Standard).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES-Typ
XAdESType
. Standardwert ist None (XAdES ist deaktiviert).
Derzeit wird der XAdES‑Signaturtyp nur für Tabellenkalkulationsdokumente unter .NET Framework unterstützt (nicht unter .NET Standard).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Überschreibe die String-Konvertierung.


**Returns:**
java.lang.String -
