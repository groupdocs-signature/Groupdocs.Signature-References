---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält Optionen zum Verifizieren der digitalen Signatur des Dokuments."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Enthält Optionen zum Verifizieren der digitalen Signatur des Dokuments.

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Erstellt Digital Verification Option mit Standardwerten. |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Erstellt Digital Verification Option mit dem angegebenen digitalen Zertifikats-GUID. |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Erstellt Digital Verification Option mit dem angegebenen Zertifikats-Stream. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCertificate()](#getCertificate--) | Ruft X509Certificate2-Zertifikat aus Zertifikats-GUID oder Stream ab. |
| [getPassword()](#getPassword--) | Passwort des digitalen Zertifikats, falls erforderlich. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Passwort des digitalen Zertifikats, falls erforderlich. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Datei-GUID des digitalen Zertifikats. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Datei-GUID des digitalen Zertifikats. |
| [getCertificateStream()](#getCertificateStream--) | Stream des digitalen Zertifikats. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Stream des digitalen Zertifikats. |
| [getComments()](#getComments--) | Kommentare der digitalen Signatur zur Validierung. |
| [setComments(String value)](#setComments-java.lang.String-) | Kommentare der digitalen Signatur zur Validierung. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Datums- und Zeitbereich der digitalen Signatur zur Validierung. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Datums- und Zeitbereich der digitalen Signatur zur Validierung. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Datums- und Zeitbereich der digitalen Signatur zur Validierung. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Datums- und Zeitbereich der digitalen Signatur zur Validierung. |
| [getReason()](#getReason--) | Grund der digitalen Signatur zur Validierung. |
| [setReason(String value)](#setReason-java.lang.String-) | Grund der digitalen Signatur zur Validierung. |
| [getContact()](#getContact--) | Signaturkontakt zur Validierung. |
| [setContact(String value)](#setContact-java.lang.String-) | Signaturkontakt zur Validierung. |
| [getLocation()](#getLocation--) | Signaturort zum Validieren. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Signaturort zum Validieren. |
| [getSubjectName()](#getSubjectName--) | Subject Distinguished Name des zu validierenden Zertifikats. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Subject Distinguished Name des zu validierenden Zertifikats. |
| [getIssuerName()](#getIssuerName--) | Issuer-Name des zu validierenden Zertifikats. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Issuer-Name des zu validierenden Zertifikats. |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Erstellt Digital Verification Option mit Standardwerten.

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Erstellt Digital Verification Option mit dem angegebenen digitalen Zertifikats-GUID.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateGuid | java.lang.String | Dateipfad zum digitalen Zertifikat. |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Erstellt Digital Verification Option mit dem angegebenen Zertifikats-Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Stream des Zertifikats. |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Ruft X509Certificate2-Zertifikat aus Zertifikats-GUID oder Stream ab.

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Passwort des digitalen Zertifikats, falls erforderlich.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Passwort des digitalen Zertifikats, falls erforderlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Datei-GUID des digitalen Zertifikats.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Datei-GUID des digitalen Zertifikats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Stream des digitalen Zertifikats.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Stream des digitalen Zertifikats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Kommentare der digitalen Signatur zur Validierung.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Kommentare der digitalen Signatur zur Validierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Datums- und Zeitbereich der zu validierenden digitalen Signatur. Nullbarer Wert wird ignoriert.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Datums- und Zeitbereich der zu validierenden digitalen Signatur. Nullbarer Wert wird ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Datums- und Zeitbereich der zu validierenden digitalen Signatur. Nullbarer Wert wird ignoriert.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Datums- und Zeitbereich der zu validierenden digitalen Signatur. Nullbarer Wert wird ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Grund der digitalen Signatur zur Validierung.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Grund der digitalen Signatur zur Validierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Signaturkontakt zur Validierung.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Signaturkontakt zur Validierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Signaturort zum Validieren.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Signaturort zum Validieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Subject Distinguished Name des zu validierenden Zertifikats. Der Wert ist case-sensitive. Wenn diese Eigenschaft gesetzt ist, prüft die Verifizierung, ob der Signature subject name den übergebenen Wert enthält oder ihm entspricht.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Subject Distinguished Name des zu validierenden Zertifikats. Der Wert ist case-sensitive. Wenn diese Eigenschaft gesetzt ist, prüft die Verifizierung, ob der Signature subject name den übergebenen Wert enthält oder ihm entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Issuer-Name des zu validierenden Zertifikats. Der Wert ist case-sensitive. Wenn diese Eigenschaft gesetzt ist, prüft die Verifizierung, ob der Signature's issuer name den übergebenen Wert enthält oder ihm entspricht.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Issuer-Name des zu validierenden Zertifikats. Der Wert ist case-sensitive. Wenn diese Eigenschaft gesetzt ist, prüft die Verifizierung, ob der Signature's issuer name den übergebenen Wert enthält oder ihm entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

