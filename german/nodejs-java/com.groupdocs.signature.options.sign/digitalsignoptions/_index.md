---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die Optionen für digitale Signaturen dar."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Stellt die Optionen für digitale Signaturen dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalSignOptions()](#DigitalSignOptions--) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit Standardwerten. |
| [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei. |
| [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikatsstream. |
| [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einer Bilddatei. |
| [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einem Bildstream. |
| [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikatsstream und einer Bilddatei. |
| [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikatsstream und einem Bildstream. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getReason()](#getReason--) | Abrufen oder Festlegen des Grundes der Signatur. |
| [setReason(String value)](#setReason-java.lang.String-) | Abrufen oder Festlegen des Grundes der Signatur. |
| [getContact()](#getContact--) | Abrufen oder Festlegen des Signaturkontakts. |
| [setContact(String value)](#setContact-java.lang.String-) | Abrufen oder Festlegen des Signaturkontakts. |
| [getLocation()](#getLocation--) | Abrufen oder Festlegen des Signaturorts. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Abrufen oder Festlegen des Signaturorts. |
| [getPassword()](#getPassword--) | Abrufen oder Festlegen des Passworts des digitalen Zertifikats. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Abrufen oder Festlegen des Passworts des digitalen Zertifikats. |
| [getSignature()](#getSignature--) | Abrufen oder Festlegen der Eigenschaften der digitalen Dokumentensignatur. |
| [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Abrufen oder Festlegen der Eigenschaften der digitalen Dokumentensignatur. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Ruft den Pfad der digitalen Zertifikatsdatei ab oder legt ihn fest. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Ruft die GUID der digitalen Zertifikatsdatei ab oder legt sie fest. |
| [getCertificateStream()](#getCertificateStream--) | Ruft den Stream des digitalen Zertifikats ab oder legt ihn fest. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Ruft den Stream des digitalen Zertifikats ab oder legt ihn fest. |
| [getVisible()](#getVisible--) | Ruft die Sichtbarkeit der Signatur ab oder legt sie fest. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ruft die Sichtbarkeit der Signatur ab oder legt sie fest. |
| [getXAdESType()](#getXAdESType--) | XAdES-Typ XAdESType. |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES-Typ XAdESType. |
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
| [toString()](#toString--) | Überschreibe die String-Konvertierung. |
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
| certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikatsstream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Stream des digitalen Zertifikats |

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einer Bilddatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
| imageFilePath | java.lang.String | Dateipfad des Bildes für das Signatur‑Erscheinungsbild |

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einer Zertifikatsdatei und einem Bildstream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
| appearenceImageStream | java.io.InputStream | Bildstream für das Signatur‑Erscheinungsbild |

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikatsstream und einer Bilddatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Stream des digitalen Zertifikats |
| imageFilePath | java.lang.String | Dateipfad des Bildes für das Signatur‑Erscheinungsbild |

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Initialisiert eine neue Instanz der Klasse DigitalSignOptions mit einem Zertifikatsstream und einem Bildstream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Stream des digitalen Zertifikats |
| appearenceImageStream | java.io.InputStream | Bildstream für das Signatur‑Erscheinungsbild |

### getReason() {#getReason--}
```
public final String getReason()
```


Abrufen oder Festlegen des Grundes der Signatur.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Abrufen oder Festlegen des Grundes der Signatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Abrufen oder Festlegen des Signaturkontakts.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Abrufen oder Festlegen des Signaturkontakts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Abrufen oder Festlegen des Signaturorts.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Abrufen oder Festlegen des Signaturorts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Abrufen oder Festlegen des Passworts des digitalen Zertifikats.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Abrufen oder Festlegen des Passworts des digitalen Zertifikats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Abrufen oder Festlegen der Eigenschaften der digitalen Dokumentensignatur.

**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Abrufen oder Festlegen der Eigenschaften der digitalen Dokumentensignatur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Ruft den Pfad der digitalen Zertifikatsdatei ab oder legt ihn fest. Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Ruft die GUID der digitalen Zertifikatsdatei ab oder legt sie fest. Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Ruft den Stream des digitalen Zertifikats ab oder legt ihn fest. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateGuid verwendet.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Ruft den Stream des digitalen Zertifikats ab oder legt ihn fest. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateGuid verwendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Ruft die Sichtbarkeit der Signatur ab oder legt sie fest.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Ruft die Sichtbarkeit der Signatur ab oder legt sie fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES‑Typ  XAdESType . Standardwert ist None (XAdES ist deaktiviert). Derzeit wird der XAdES‑Signaturtyp nur für Spreadsheet‑Dokumente unter .NET Framework unterstützt (nicht unter .NET Standard).

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES‑Typ  XAdESType . Standardwert ist None (XAdES ist deaktiviert). Derzeit wird der XAdES‑Signaturtyp nur für Spreadsheet‑Dokumente unter .NET Framework unterstützt (nicht unter .NET Standard).

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
