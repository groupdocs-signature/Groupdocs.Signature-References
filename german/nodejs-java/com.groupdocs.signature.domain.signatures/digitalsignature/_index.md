---
title: "DigitalSignature"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Enthält digitale Signatur‑Eigenschaften."
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Enthält digitale Signatur‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalSignature()](#DigitalSignature--) | Initialisieren Sie die digitale Signatur mit Standardparametern. |
| [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Initialisieren Sie die digitale Signatur mit einer bekannten SignatureId. |
| [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Erstellen Sie eine digitale Signatur mit dem angegebenen Zertifikat. |
| [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Erstellen Sie eine digitale Signatur basierend auf dem X509Certificate-Zertifikat und dem PrivateKey. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCertificate()](#getCertificate--) | Liest oder setzt das KeyStore-Zertifikat. |
| [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Liest oder setzt das KeyStore-Zertifikat. |
| [getX509Certificate()](#getX509Certificate--) | Liest oder setzt das X509-Zertifikat. |
| [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Liest oder setzt das X509-Zertifikat. |
| [getPrivateKey()](#getPrivateKey--) | Liest oder setzt den PrivateKey des Zertifikats. |
| [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Liest oder setzt den PrivateKey des Zertifikats. |
| [getCertificateName()](#getCertificateName--) | Liest oder setzt den Namen des X509-Zertifikats. |
| [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Liest oder setzt den Namen des X509-Zertifikats. |
| [getComments()](#getComments--) | Liest oder setzt den Kommentar zum Signaturzweck. |
| [setComments(String value)](#setComments-java.lang.String-) | Liest oder setzt den Kommentar zum Signaturzweck. |
| [isValid()](#isValid--) | Ist wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde. |
| [setValid(boolean value)](#setValid-boolean-) | Ist wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde. |
| [getSignTime()](#getSignTime--) | Liest oder setzt den Zeitpunkt, zu dem das Dokument signiert wurde. |
| [setSignTime(Date value)](#setSignTime-java.util.Date-) | Liest oder setzt den Zeitpunkt, zu dem das Dokument signiert wurde. |
| [getXAdESType()](#getXAdESType--) | XAdES-Typ XAdESType. |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES-Typ XAdESType. |
| [getThumbprint()](#getThumbprint--) | Liest den Fingerabdruck eines Zertifikats. |
| [equals(Object signature)](#equals-java.lang.Object-) | Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen |
| [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
| [deepClone()](#deepClone--) | Klont die Barcode-Signatur-Instanz. |
| [loadDigitalSignatures()](#loadDigitalSignatures--) | Lädt die digitale Signatur aus allen System-X509-Zertifikatspeichern. |
| [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Lädt die digitale Signatur aus dem übergebenen X509-Zertifikatspeicher. |
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Initialisieren Sie die digitale Signatur mit Standardparametern.

### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Initialisieren Sie die digitale Signatur mit einer bekannten SignatureId.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Erstellen Sie eine digitale Signatur mit dem angegebenen Zertifikat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zertifikat | java.security.KeyStore | X509-Zertifikat. |

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Erstellen Sie eine digitale Signatur basierend auf dem X509Certificate-Zertifikat und dem PrivateKey.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cert | java.security.cert.X509Certificate | X509Certificate Zertifikat. |
| Schlüssel | java.security.PrivateKey | PrivateKey des Zertifikats. |

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Liest oder setzt das KeyStore-Zertifikat.

**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Liest oder setzt das KeyStore-Zertifikat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Liest oder setzt das X509-Zertifikat.

**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Liest oder setzt das X509-Zertifikat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Liest oder setzt den PrivateKey des Zertifikats.

**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Liest oder setzt den PrivateKey des Zertifikats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Liest oder setzt den Namen des X509-Zertifikats.

**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Liest oder setzt den Namen des X509-Zertifikats.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Liest oder setzt den Kommentar zum Signaturzweck.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Liest oder setzt den Kommentar zum Signaturzweck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Ist wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Ist wahr, wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Liest oder setzt den Zeitpunkt, zu dem das Dokument signiert wurde.

**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Liest oder setzt den Zeitpunkt, zu dem das Dokument signiert wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES Typ XAdESType. Standardwert ist Keine (XAdES ist deaktiviert). In diesem Moment wird der XAdES-Signaturtyp nur für Tabellenkalkulationsdokumente unterstützt.

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES Typ XAdESType. Standardwert ist Keine (XAdES ist deaktiviert). In diesem Moment wird der XAdES-Signaturtyp nur für Tabellenkalkulationsdokumente unterstützt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Liest den Fingerabdruck eines Zertifikats.

**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Überschreibt die Equals-Methode, um Signatur-Eigenschaften zu vergleichen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Signatur | java.lang.Object | Signatur-Objekt zum Vergleichen. |

**Returns:**
boolean - Gibt true zurück, wenn das übergebene Signatur-Objekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.
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


Klont die Barcode-Signatur-Instanz.

**Returns:**
java.lang.Object - Gibt eine geklonte Barcode-Signatur-Instanz zurück.
### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Lädt die digitale Signatur aus allen System-X509-Zertifikatspeichern.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Gibt eine Liste von [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) digitalen Signaturen zurück.
### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Lädt die digitale Signatur aus dem übergebenen X509-Zertifikatspeicher.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Gibt eine Liste von [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) digitalen Signaturen zurück.
