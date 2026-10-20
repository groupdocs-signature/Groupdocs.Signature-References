---
title: "DigitalSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen van digitale handtekening."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Bevat eigenschappen van digitale handtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | Initialiseer digitale handtekening met standaardparameters. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Initialiseer digitale handtekening met bekende SignatureId. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Maak digitale handtekening met opgegeven certificaat. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Maak digitale handtekening op basis van X509Certificate certificaat en PrivateKey. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Haalt op of stelt het KeyStore-certificaat in. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Haalt op of stelt het KeyStore-certificaat in. |
|
|  | [getX509Certificate()](#getX509Certificate--) | Haalt op of stelt het X509-certificaat in. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | Haalt op of stelt het X509-certificaat in. |
|
|  | [getPrivateKey()](#getPrivateKey--) | Haalt op of stelt de PrivateKey van het certificaat in. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | Haalt op of stelt de PrivateKey van het certificaat in. |
|
|  | [getCertificateName()](#getCertificateName--) | Haalt op of stelt de X509-certificaatnaam in. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | Haalt op of stelt de X509-certificaatnaam in. |
|
|  | [getComments()](#getComments--) | Haalt op of stelt de ondertekeningsdoelopmerking in. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Haalt op of stelt de ondertekeningsdoelopmerking in. |
|
|  | [isValid()](#isValid--) | Blijft true als deze digitale handtekening geldig is en het document niet is gemanipuleerd. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Blijft true als deze digitale handtekening geldig is en het document niet is gemanipuleerd. |
|
|  | [getSignTime()](#getSignTime--) | Haalt op of stelt de tijd in waarop het document is ondertekend. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | Haalt op of stelt de tijd in waarop het document is ondertekend. |
|
|  | [getXAdESType()](#getXAdESType--) | XAdES-type |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES-type |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | Haalt de thumbprint van een certificaat op. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Barcode Signature‑instantie. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | Laad digitale handtekening vanuit alle systeem X509-certificaatopslagplaatsen. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | Laad digitale handtekening vanuit meegegeven X509-certificaatopslagplaats. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Initialiseer digitale handtekening met standaardparameters.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Initialiseer digitale handtekening met bekende SignatureId.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Maak digitale handtekening met opgegeven certificaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificaat | java.security.KeyStore | X509 certificaat. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


Maak digitale handtekening op basis van X509Certificate certificaat en PrivateKey.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | X509Certificate certificaat. |
|
|  | key | java.security.PrivateKey | PrivateKey van certificaat. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Haalt op of stelt het KeyStore-certificaat in.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Haalt op of stelt het KeyStore-certificaat in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


Haalt op of stelt het X509-certificaat in.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


Haalt op of stelt het X509-certificaat in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


Haalt op of stelt de PrivateKey van het certificaat in.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


Haalt op of stelt de PrivateKey van het certificaat in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


Haalt op of stelt de X509-certificaatnaam in.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


Haalt op of stelt de X509-certificaatnaam in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Haalt op of stelt de ondertekeningsdoelopmerking in.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Haalt op of stelt de ondertekeningsdoelopmerking in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Blijft true als deze digitale handtekening geldig is en het document niet is gemanipuleerd.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Blijft true als deze digitale handtekening geldig is en het document niet is gemanipuleerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Haalt op of stelt de tijd in waarop het document is ondertekend.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Haalt op of stelt de tijd in waarop het document is ondertekend.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES-type
XAdESType
 . Standaardwaarde is None (XAdES is uit).
Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES-type
XAdESType
 . Standaardwaarde is None (XAdES is uit).
Op dit moment wordt het XAdES-handtekeningtype alleen ondersteund voor Spreadsheet-documenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Haalt de thumbprint van een certificaat op.


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | handtekening | java.lang.Object | Handtekeningobject om mee te vergelijken. |
|

**Returns:**
boolean - Retourneert true als het meegegeven handtekeningobject hetzelfde type heeft en al zijn eigenschappen gelijk zijn aan de eigenschappen van deze instantie.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Overschrijft de GetHashCode‑methode


**Returns:**
int - Handtekening hashcode

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Kloon Barcode Signature‑instantie.


**Returns:**
java.lang.Object - Retourneert een gekloonde Barcode-handtekening‑instantie.

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Laad digitale handtekening vanuit alle systeem X509-certificaatopslagplaatsen.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Retourneert een lijst van [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digitale Handtekeningen.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


Laad digitale handtekening vanuit meegegeven X509-certificaatopslagplaats.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Retourneert een lijst van [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digitale Handtekeningen.

