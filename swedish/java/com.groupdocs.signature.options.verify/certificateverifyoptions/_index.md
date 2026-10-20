---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Behåller alternativ för att verifiera certifikatdokument."
type: docs
weight: 11
url: /sv/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

Behåller alternativ för att verifiera certifikatdokument.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | Initierar en ny instans av TextVerifyOptions med standardvärden. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | Initierar en ny instans av CertificateVerifyOptions med ämnet att verifiera. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | Ange certifikatutfärdare om den ska verifieras. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | Ange certifikatutfärdare om den ska verifieras. |
|
|  | [getSerialNumber()](#getSerialNumber--) | Ange certifikatets serienummer om den ska verifieras. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Ange certifikatets serienummer om den ska verifieras. |
|
|  | [getSubject()](#getSubject--) | Ange certifikatets ämne om det ska verifieras. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | Ange certifikatets ämne om det ska verifieras. |
|
|  | [getThumbprint()](#getThumbprint--) | Ange certifikatets fingeravtryck om det ska verifieras. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | Ange certifikatets fingeravtryck om det ska verifieras. |
|
|  | [getMatchType()](#getMatchType--) | Hämtar eller anger verifiering av textmatchningstyp. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Hämtar eller anger verifiering av textmatchningstyp. |
|
|  | [getExpired()](#getExpired--) | Anger om certifikatet har utgånget datum på grund av valideringsresultatet. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | Anger om certifikatet har utgånget datum på grund av valideringsresultatet. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | Hämta eller ange om verifieringsprocessen ska tillhandahålla X.509-kedjevalidering med grundläggande valideringspolicy. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | Hämta eller ange om verifieringsprocessen ska tillhandahålla X.509-kedjevalidering med grundläggande valideringspolicy. |
|
|  | [toString()](#toString--) | Åsidosätter konvertering till sträng. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


Initierar en ny instans av TextVerifyOptions med standardvärden.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


Initierar en ny instans av CertificateVerifyOptions med ämnet att verifiera.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ämne | java.lang.String | Ämne att verifiera |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


Ange certifikatutfärdare om den ska verifieras.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


Ange certifikatutfärdare om den ska verifieras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


Ange certifikatets serienummer om den ska verifieras.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


Ange certifikatets serienummer om den ska verifieras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Ange certifikatets ämne om det ska verifieras.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Ange certifikatets ämne om det ska verifieras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Ange certifikatets fingeravtryck om det ska verifieras.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


Ange certifikatets fingeravtryck om det ska verifieras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Hämtar eller anger verifiering av textmatchningstyp.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Hämtar eller anger verifiering av textmatchningstyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


Anger om certifikatet har utgånget datum på grund av valideringsresultatet.
Egenskapen är skrivskyddad.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


Anger om certifikatet har utgånget datum på grund av valideringsresultatet.
Egenskapen är skrivskyddad.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


Hämta eller ange om verifieringsprocessen ska tillhandahålla X.509-kedjevalidering med grundläggande valideringspolicy.
Som standard är detta värde sant.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


Hämta eller ange om verifieringsprocessen ska tillhandahålla X.509-kedjevalidering med grundläggande valideringspolicy.
Som standard är detta värde sant.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätter konvertering till sträng.


**Returns:**
java.lang.String -
