---
title: "DigitalVerifyOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Conserve les options pour vérifier la signature numérique du document."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Conserve les options pour vérifier la signature numérique du document.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Crée Digital Verification Option avec des valeurs par défaut. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Crée Digital Verification Option avec le guid du certificat numérique fourni. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Crée Digital Verification Option avec le flux du certificat fourni. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Obtient le certificat X509Certificate2 à partir du guid du certificat ou du flux. |
|
|  | [getPassword()](#getPassword--) | Mot de passe du certificat numérique si nécessaire. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mot de passe du certificat numérique si nécessaire. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Guid du fichier du certificat numérique. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Guid du fichier du certificat numérique. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Flux du certificat numérique. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Flux du certificat numérique. |
|
|  | [getComments()](#getComments--) | Commentaires de la signature numérique à valider. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Commentaires de la signature numérique à valider. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Plage de date et d'heure de la signature numérique à valider. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Plage de date et d'heure de la signature numérique à valider. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Plage de date et d'heure de la signature numérique à valider. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Plage de date et d'heure de la signature numérique à valider. |
|
|  | [getReason()](#getReason--) | Raison de la signature numérique à valider. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Raison de la signature numérique à valider. |
|
|  | [getContact()](#getContact--) | Contact de la signature à valider. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Contact de la signature à valider. |
|
|  | [getLocation()](#getLocation--) | Lieu de la signature à valider. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Lieu de la signature à valider. |
|
|  | [getSubjectName()](#getSubjectName--) | Nom distinctif du sujet du certificat à valider. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Nom distinctif du sujet du certificat à valider. |
|
|  | [getIssuerName()](#getIssuerName--) | Nom de l'émetteur du certificat à valider. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Nom de l'émetteur du certificat à valider. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Crée Digital Verification Option avec des valeurs par défaut.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Crée Digital Verification Option avec le guid du certificat numérique fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Chemin du fichier du certificat numérique. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Crée Digital Verification Option avec le flux du certificat fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Flux du certificat. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Obtient le certificat X509Certificate2 à partir du guid du certificat ou du flux.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mot de passe du certificat numérique si nécessaire.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mot de passe du certificat numérique si nécessaire.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Guid du fichier du certificat numérique.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Guid du fichier du certificat numérique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Flux du certificat numérique.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Flux du certificat numérique.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Commentaires de la signature numérique à valider.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Commentaires de la signature numérique à valider.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Plage de date et d'heure de la signature numérique à valider. La valeur nullable sera ignorée.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Plage de date et d'heure de la signature numérique à valider. La valeur nullable sera ignorée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Plage de date et d'heure de la signature numérique à valider. La valeur nullable sera ignorée.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Plage de date et d'heure de la signature numérique à valider. La valeur nullable sera ignorée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Raison de la signature numérique à valider.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Raison de la signature numérique à valider.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Contact de la signature à valider.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Contact de la signature à valider.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Lieu de la signature à valider.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Lieu de la signature à valider.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Nom distinctif du sujet du certificat à valider. La valeur est sensible à la casse.
Si cette propriété est définie, la vérification vérifiera si le nom du sujet de la signature contient ou est égal à la valeur fournie.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Nom distinctif du sujet du certificat à valider. La valeur est sensible à la casse.
Si cette propriété est définie, la vérification vérifiera si le nom du sujet de la signature contient ou est égal à la valeur fournie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Nom de l'émetteur du certificat à valider. La valeur est sensible à la casse.
Si cette propriété est définie, la vérification vérifiera si le nom de l'émetteur de la signature contient ou est égal à la valeur fournie.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Nom de l'émetteur du certificat à valider. La valeur est sensible à la casse.
Si cette propriété est définie, la vérification vérifiera si le nom de l'émetteur de la signature contient ou est égal à la valeur fournie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

