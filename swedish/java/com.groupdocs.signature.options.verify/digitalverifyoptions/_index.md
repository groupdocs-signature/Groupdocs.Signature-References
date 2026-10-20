---
title: "DigitalVerifieringsalternativ"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Behåller alternativ för att verifiera dokumentets Digital-signatur."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Behåller alternativ för att verifiera dokumentets Digital-signatur.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Skapar DigitalVerifieringsalternativ med standardvärden. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Skapar DigitalVerifieringsalternativ med angivet digitalt certifikat‑guid. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Skapar DigitalVerifieringsalternativ med angiven certifikatström. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Hämta X509Certificate2‑certifikat från certifikat‑guid eller ström. |
|
|  | [getPassword()](#getPassword--) | Lösenord för digitalt certifikat om det krävs. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Lösenord för digitalt certifikat om det krävs. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Fil‑guid för digitalt certifikat. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Fil‑guid för digitalt certifikat. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Ström för digitalt certifikat. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Ström för digitalt certifikat. |
|
|  | [getComments()](#getComments--) | Kommentarer för digital signatur att validera. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Kommentarer för digital signatur att validera. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Datum‑ och tidsintervall för digital signatur att validera. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Datum‑ och tidsintervall för digital signatur att validera. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Datum‑ och tidsintervall för digital signatur att validera. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Datum‑ och tidsintervall för digital signatur att validera. |
|
|  | [getReason()](#getReason--) | Orsak till digital signatur att validera. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Orsak till digital signatur att validera. |
|
|  | [getContact()](#getContact--) | Signaturkontakt att validera. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | Signaturkontakt att validera. |
|
|  | [getLocation()](#getLocation--) | Signaturplats att validera. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | Signaturplats att validera. |
|
|  | [getSubjectName()](#getSubjectName--) | Subject distinguished name för certifikatet att validera. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Subject distinguished name för certifikatet att validera. |
|
|  | [getIssuerName()](#getIssuerName--) | Utfärdarens namn för certifikatet att validera. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Utfärdarens namn för certifikatet att validera. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Skapar DigitalVerifieringsalternativ med standardvärden.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Skapar DigitalVerifieringsalternativ med angivet digitalt certifikat‑guid.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | Filväg till digitalt certifikat. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Skapar DigitalVerifieringsalternativ med angiven certifikatström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | Certifikatets ström. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Hämta X509Certificate2‑certifikat från certifikat‑guid eller ström.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Lösenord för digitalt certifikat om det krävs.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Lösenord för digitalt certifikat om det krävs.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Fil‑guid för digitalt certifikat.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Fil‑guid för digitalt certifikat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Ström för digitalt certifikat.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Ström för digitalt certifikat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Kommentarer för digital signatur att validera.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Kommentarer för digital signatur att validera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Datum- och tidsintervall för digital signatur att validera. Nullbart värde kommer att ignoreras.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Datum- och tidsintervall för digital signatur att validera. Nullbart värde kommer att ignoreras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Datum- och tidsintervall för digital signatur att validera. Nullbart värde kommer att ignoreras.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Datum- och tidsintervall för digital signatur att validera. Nullbart värde kommer att ignoreras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Orsak till digital signatur att validera.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Orsak till digital signatur att validera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Signaturkontakt att validera.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Signaturkontakt att validera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Signaturplats att validera.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Signaturplats att validera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Subject distinguished name för certifikatet att validera. Värdet är skiftlägeskänsligt.
Om den här egenskapen är inställd kommer verifieringen att kontrollera om Signature subject name innehåller eller är lika med det angivna värdet.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Subject distinguished name för certifikatet att validera. Värdet är skiftlägeskänsligt.
Om den här egenskapen är inställd kommer verifieringen att kontrollera om Signature subject name innehåller eller är lika med det angivna värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Utfärdarens namn för certifikatet att validera. Värdet är skiftlägeskänsligt.
Om den här egenskapen är inställd kommer verifieringen att kontrollera om signaturens utfärdarnamn innehåller eller är lika med det angivna värdet.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Utfärdarens namn för certifikatet att validera. Värdet är skiftlägeskänsligt.
Om den här egenskapen är inställd kommer verifieringen att kontrollera om signaturens utfärdarnamn innehåller eller är lika med det angivna värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

