---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat opties om certificaatdocumenten te verifiëren."
type: docs
weight: 11
url: /nl/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Bevat opties om certificaatdocumenten te verifiëren.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van CertificateVerifyOptions met het te verifiëren onderwerp. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Geef de certificaatuitgever op als deze moet worden geverifieerd. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Geef de certificaatuitgever op als deze moet worden geverifieerd. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Geef het certificaatserienummer op als dit moet worden geverifieerd. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Geef het certificaatserienummer op als dit moet worden geverifieerd. |
|
|  | [getSubject()](#getSubject--) | Geef het certificaatonderwerp op als dit moet worden geverifieerd. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Geef het certificaatonderwerp op als dit moet worden geverifieerd. |
|
|  | [getThumbprint()](#getThumbprint--) | Geef de certificaatvingerafdruk op als deze moet worden geverifieerd. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Geef de certificaatvingerafdruk op als deze moet worden geverifieerd. |
|
|  | [getMatchType()](#getMatchType--) | Haalt op of stelt verificatie van tekstovereenkomsttype in. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Haalt op of stelt verificatie van tekstovereenkomsttype in. |
|
|  | [getExpired()](#getExpired--) | Geeft aan of het certificaat verlopen is op basis van het validatieresultaat. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Geeft aan of het certificaat verlopen is op basis van het validatieresultaat. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Haalt op of stelt in of het verificatieproces X.509-ketenvalidatie moet uitvoeren met behulp van het basisvalidatiebeleid. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Haalt op of stelt in of het verificatieproces X.509-ketenvalidatie moet uitvoeren met behulp van het basisvalidatiebeleid. |
|
|  | [toString()](#toString--) | Overschrijft conversie naar string. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Initialiseert een nieuw exemplaar van CertificateVerifyOptions met het te verifiëren onderwerp.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | subject | java.lang.String | Te verifiëren onderwerp |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Geef de certificaatuitgever op als deze moet worden geverifieerd.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Geef de certificaatuitgever op als deze moet worden geverifieerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Geef het certificaatserienummer op als dit moet worden geverifieerd.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Geef het certificaatserienummer op als dit moet worden geverifieerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Geef het certificaatonderwerp op als dit moet worden geverifieerd.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Geef het certificaatonderwerp op als dit moet worden geverifieerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Geef de certificaatvingerafdruk op als deze moet worden geverifieerd.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Geef de certificaatvingerafdruk op als deze moet worden geverifieerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Haalt op of stelt verificatie van tekstovereenkomsttype in.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Haalt op of stelt verificatie van tekstovereenkomsttype in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Geeft aan of het certificaat verlopen is op basis van het validatieresultaat.
Eigenschap is alleen-lezen.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Geeft aan of het certificaat verlopen is op basis van het validatieresultaat.
Eigenschap is alleen-lezen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Haalt op of stelt in of het verificatieproces X.509-ketenvalidatie moet uitvoeren met behulp van het basisvalidatiebeleid.
Standaard is deze waarde true.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Haalt op of stelt in of het verificatieproces X.509-ketenvalidatie moet uitvoeren met behulp van het basisvalidatiebeleid.
Standaard is deze waarde true.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijft conversie naar string.


**Returns:**
java.lang.String -
