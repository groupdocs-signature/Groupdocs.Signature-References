---
title: "DigitalSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för digital signatur."
type: docs
weight: 12
url: /sv/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Innehåller egenskaper för digital signatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Initiera Digital signature med standardparametrar. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Initiera Digital signature med känt SignatureId. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Skapa Digital signature med angivet certifikat. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Skapa Digital signature baserat på X509Certificate-certifikat och PrivateKey. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Hämtar eller anger KeyStore-certifikatet. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Hämtar eller anger KeyStore-certifikatet. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Hämtar eller anger X509-certifikatet. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Hämtar eller anger X509-certifikatet. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Hämtar eller anger PrivateKey för certifikatet. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Hämtar eller anger PrivateKey för certifikatet. |
|
|  | [getCertificateName()](#getCertificateName--) | Hämtar eller anger X509-certifikatnamnet. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Hämtar eller anger X509-certifikatnamnet. |
|
|  | [getComments()](#getComments--) | Hämtar eller anger kommentaren för signeringsändamål. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Hämtar eller anger kommentaren för signeringsändamål. |
|
|  | [isValid()](#isValid--) | Behåller true om denna digitala signatur är giltig och dokumentet inte har manipulerats. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Behåller true om denna digitala signatur är giltig och dokumentet inte har manipulerats. |
|
|  | [getSignTime()](#getSignTime--) | Hämtar eller anger tiden då dokumentet signerades. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Hämtar eller anger tiden då dokumentet signerades. |
|
|  | [getXAdESType()](#getXAdESType--) | XAdES-typ |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES-typ |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Hämtar fingeravtrycket för ett certifikat. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Barcode Signature-instans. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Läs in Digital signature från alla system X509-certifikatlagringar. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Läs in Digital signature från angiven X509-certifikatlagring. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Initiera Digital signature med standardparametrar.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Initiera Digital signature med känt SignatureId.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Skapa Digital signature med angivet certifikat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certifikat | java.security.KeyStore | X509-certifikat. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Skapa Digital signature baserat på X509Certificate-certifikat och PrivateKey.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | X509Certificate certifikat. |
|
|  | nyckel | java.security.PrivateKey | PrivateKey för certifikat. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Hämtar eller anger KeyStore-certifikatet.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Hämtar eller anger KeyStore-certifikatet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Hämtar eller anger X509-certifikatet.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Hämtar eller anger X509-certifikatet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Hämtar eller anger PrivateKey för certifikatet.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Hämtar eller anger PrivateKey för certifikatet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Hämtar eller anger X509-certifikatnamnet.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Hämtar eller anger X509-certifikatnamnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Hämtar eller anger kommentaren för signeringsändamål.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Hämtar eller anger kommentaren för signeringsändamål.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Behåller true om denna digitala signatur är giltig och dokumentet inte har manipulerats.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Behåller true om denna digitala signatur är giltig och dokumentet inte har manipulerats.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Hämtar eller anger tiden då dokumentet signerades.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Hämtar eller anger tiden då dokumentet signerades.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES-typ
XAdESType
. Standardvärdet är None (XAdES är avstängt).
För närvarande stöds XAdES-signaturtypen endast för kalkylbladsdokument.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES-typ
XAdESType
. Standardvärdet är None (XAdES är avstängt).
För närvarande stöds XAdES-signaturtypen endast för kalkylbladsdokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Hämtar fingeravtrycket för ett certifikat.


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Skriver över Equals-metoden för att jämföra signaturens egenskaper


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatur | java.lang.Object | Signaturobjekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda signaturobjektet har samma typ och alla dess egenskaper är lika med egenskaperna i denna instans.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - Signaturens hashkod

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Klona Barcode Signature-instans.


**Returns:**
java.lang.Object - Returnerar en klonad Barcode Signature-instans.

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Läs in Digital signature från alla system X509-certifikatlagringar.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Returnerar lista med [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digitala signaturer.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Läs in Digital signature från angiven X509-certifikatlagring.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Returnerar lista med [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digitala signaturer.

