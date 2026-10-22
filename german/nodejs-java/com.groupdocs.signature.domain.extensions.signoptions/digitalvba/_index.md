---
title: "DigitalVBA"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Stellt die digitale Signatur für VBA-Projekte von Tabellenkalkulationen dar."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Stellt die digitale Signatur für Spreadsheets-VBA-Projekte dar. Sie bietet die Möglichkeit, VBA-Projekte in bestimmten Spreadsheets-Dokumentformaten wie Xlsm oder Xltm zu signieren. Wenn mehrere DigitalVBA-Erweiterungen zu DigitalSignOptions.Extensions hinzugefügt werden, ist nur die erste an der Dokumentensignatur beteiligt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einer Zertifikatsdatei. |
| [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einem Zertifikats-Stream. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getComments()](#getComments--) | Liest oder setzt die Signaturkommentare. |
| [setComments(String value)](#setComments-java.lang.String-) | Liest oder setzt die Signaturkommentare. |
| [getPassword()](#getPassword--) | Abrufen oder Festlegen des Passworts des digitalen Zertifikats. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Abrufen oder Festlegen des Passworts des digitalen Zertifikats. |
| [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Liest oder setzt die Einstellung für das Signieren nur des VBA-Projekts. |
| [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Liest oder setzt die Einstellung für das Signieren nur des VBA-Projekts. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Liest den Pfad zur digitalen Zertifikatsdatei. |
| [getCertificateStream()](#getCertificateStream--) | Liest den digitalen Zertifikat-Stream. |
| [release()](#release--) | Überschreibt die Methode, um Ressourcen nach dem Signieren aufzuräumen. |
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einer Zertifikatsdatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
| passwort | java.lang.String | Passwort für das digitale Zertifikat |

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Initialisiert eine neue Instanz der DigitalVBA-Klasse mit einem Zertifikats-Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Stream des digitalen Zertifikats |
| passwort | java.lang.String | Passwort für das digitale Zertifikat |

### getComments() {#getComments--}
```
public final String getComments()
```


Liest oder setzt die Signaturkommentare.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Liest oder setzt die Signaturkommentare.

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

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Liest oder setzt die Einstellung für das Signieren nur des VBA-Projekts. Wenn auf true gesetzt, wird das SpreadSheet-Dokument nicht signiert, aber das VBA-Projekt wird signiert.

**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Liest oder setzt die Einstellung für das Signieren nur des VBA-Projekts. Wenn auf true gesetzt, wird das SpreadSheet-Dokument nicht signiert, aber das VBA-Projekt wird signiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Liest den Pfad zur digitalen Zertifikatsdatei. Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist.

**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Liest den digitalen Zertifikat-Stream. Wenn diese Eigenschaft angegeben ist, wird sie immer anstelle von CertificateFilePath verwendet.

**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Überschreibt die Methode, um Ressourcen nach dem Signieren aufzuräumen.

