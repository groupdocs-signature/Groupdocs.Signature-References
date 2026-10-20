---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat opties om de digitale handtekening van een document te verifiëren."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Bevat opties om de digitale handtekening van een document te verifiëren.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Maakt digitale verificatie‑optie aan met standaardwaarden. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Maakt digitale verificatie‑optie aan met opgegeven digitale certificaat‑guid. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Maakt digitale verificatie‑optie aan met opgegeven certificaat‑stream. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Haal X509Certificate2‑certificaat op van certificaat‑guid of -stream. |
|
|  | [getPassword()](#getPassword--) | Wachtwoord van digitaal certificaat indien vereist. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Wachtwoord van digitaal certificaat indien vereist. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Bestand‑guid van digitaal certificaat. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Bestand‑guid van digitaal certificaat. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Stream van digitaal certificaat. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Stream van digitaal certificaat. |
|
|  | [getComments()](#getComments--) | Opmerkingen van digitale handtekening om te valideren. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Opmerkingen van digitale handtekening om te valideren. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Datum‑ en tijdsbereik van digitale handtekening om te valideren. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Datum‑ en tijdsbereik van digitale handtekening om te valideren. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Datum‑ en tijdsbereik van digitale handtekening om te valideren. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Datum‑ en tijdsbereik van digitale handtekening om te valideren. |
|
|  | [getReason()](#getReason--) | Reden van digitale handtekening om te valideren. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Reden van digitale handtekening om te valideren. |
|
|  | [getContact()](#getContact--) | Handtekeningcontact om te valideren. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Handtekeningcontact om te valideren. |
|
|  | [getLocation()](#getLocation--) | Handtekeninglocatie om te valideren. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Handtekeninglocatie om te valideren. |
|
|  | [getSubjectName()](#getSubjectName--) | Subject distinguished name van het certificaat om te valideren. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Subject distinguished name van het certificaat om te valideren. |
|
|  | [getIssuerName()](#getIssuerName--) | Naam van de uitgever van het certificaat dat moet worden gevalideerd. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Naam van de uitgever van het certificaat dat moet worden gevalideerd. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Maakt digitale verificatie‑optie aan met standaardwaarden.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Maakt digitale verificatie‑optie aan met opgegeven digitale certificaat‑guid.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Bestandspad naar het digitale certificaat. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Maakt digitale verificatie‑optie aan met opgegeven certificaat‑stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Stream van het certificaat. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Haal X509Certificate2‑certificaat op van certificaat‑guid of -stream.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Wachtwoord van digitaal certificaat indien vereist.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Wachtwoord van digitaal certificaat indien vereist.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Bestand‑guid van digitaal certificaat.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Bestand‑guid van digitaal certificaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Stream van digitaal certificaat.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Stream van digitaal certificaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Opmerkingen van digitale handtekening om te valideren.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Opmerkingen van digitale handtekening om te valideren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Datum- en tijdsbereik van de digitale handtekening die moet worden gevalideerd. Null-waarde wordt genegeerd.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Datum- en tijdsbereik van de digitale handtekening die moet worden gevalideerd. Null-waarde wordt genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Datum- en tijdsbereik van de digitale handtekening die moet worden gevalideerd. Null-waarde wordt genegeerd.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Datum- en tijdsbereik van de digitale handtekening die moet worden gevalideerd. Null-waarde wordt genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Reden van digitale handtekening om te valideren.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Reden van digitale handtekening om te valideren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Handtekeningcontact om te valideren.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Handtekeningcontact om te valideren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Handtekeninglocatie om te valideren.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Handtekeninglocatie om te valideren.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Gedistingeerde naam van het onderwerp van het certificaat dat moet worden gevalideerd. Waarde is hoofdlettergevoelig.
Als deze eigenschap is ingesteld, controleert de verificatie of de ondertekeningsonderwerpsnaam de opgegeven waarde bevat of gelijk is.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Gedistingeerde naam van het onderwerp van het certificaat dat moet worden gevalideerd. Waarde is hoofdlettergevoelig.
Als deze eigenschap is ingesteld, controleert de verificatie of de ondertekeningsonderwerpsnaam de opgegeven waarde bevat of gelijk is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Naam van de uitgever van het certificaat dat moet worden gevalideerd. Waarde is hoofdlettergevoelig.
Als deze eigenschap is ingesteld, controleert de verificatie of de uitgeversnaam van de handtekening de opgegeven waarde bevat of gelijk is.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Naam van de uitgever van het certificaat dat moet worden gevalideerd. Waarde is hoofdlettergevoelig.
Als deze eigenschap is ingesteld, controleert de verificatie of de uitgeversnaam van de handtekening de opgegeven waarde bevat of gelijk is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

