---
title: "DigitalVBA"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt die digitale Signatur für VBA-Projekte von Tabellenkalkulationen dar."
type: docs
weight: 10
url: /de/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

Stellt die digitale Signatur für VBA-Projekte von Tabellenkalkulationen dar.
Sie bietet die Möglichkeit, VBA‑Projekte in bestimmten Tabellenkalkulations‑Dokumentformaten wie Xlsm oder Xltm zu signieren.
Wenn mehrere DigitalVBA‑Erweiterungen zu DigitalSignOptions.Extensions hinzugefügt werden, ist nur die erste an der Dokumentensignatur beteiligt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalVBA mit einer Zertifikatsdatei. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | Initialisiert eine neue Instanz der Klasse DigitalVBA mit einem Zertifikats-Stream. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getComments()](#getComments--) | Liest oder setzt die Signaturkommentare. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Liest oder setzt die Signaturkommentare. |
|
|  | [getPassword()](#getPassword--) | Liest oder setzt das Passwort des digitalen Zertifikats. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das Passwort des digitalen Zertifikats. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | Liest oder setzt die Einstellung für das Signieren ausschließlich des VBA-Projekts. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | Liest oder setzt die Einstellung für das Signieren ausschließlich des VBA-Projekts. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Liest den Pfad zur digitalen Zertifikatsdatei. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Liest den Stream des digitalen Zertifikats. |
|
|  | [release()](#release--) | Überschreibt die Methode, um Ressourcen nach dem Signieren aufzuräumen. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


Initialisiert eine neue Instanz der Klasse DigitalVBA mit einer Zertifikatsdatei.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | Pfad der digitalen Zertifikatsdatei |
|
|  | Passwort | java.lang.String | Passwort für das digitale Zertifikat |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


Initialisiert eine neue Instanz der Klasse DigitalVBA mit einem Zertifikats-Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Digitaler Zertifikat-Stream |
|
|  | Passwort | java.lang.String | Passwort für das digitale Zertifikat |
|

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

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


Liest oder setzt die Einstellung für das Signieren ausschließlich des VBA-Projekts.
Wenn auf true gesetzt, wird das SpreadSheet-Dokument nicht signiert, aber das VBA-Projekt wird signiert.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


Liest oder setzt die Einstellung für das Signieren ausschließlich des VBA-Projekts.
Wenn auf true gesetzt, wird das SpreadSheet-Dokument nicht signiert, aber das VBA-Projekt wird signiert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Liest den Pfad zur digitalen Zertifikatsdatei.
Diese Eigenschaft wird nur verwendet, wenn CertificateStream nicht angegeben ist.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Liest den Stream des digitalen Zertifikats.
Wenn diese Eigenschaft angegeben ist, wird sie stets anstelle von CertificateFilePath verwendet.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


Überschreibt die Methode, um Ressourcen nach dem Signieren aufzuräumen.


