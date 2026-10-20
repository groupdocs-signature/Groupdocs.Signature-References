---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen van PDF digitale handtekening."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Bevat eigenschappen van PDF digitale handtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Initialiseer Pdf Digital Signature zonder certificaat. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Maak Pdf Digital signature aan met een opgegeven certificaat. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Informatie verstrekt door de ondertekenaar om een ontvanger in staat te stellen contact op te nemen met de ondertekenaar |
om de handtekening te verifiëren, bijv.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Informatie verstrekt door de ondertekenaar om een ontvanger in staat te stellen contact op te nemen met de ondertekenaar |
om de handtekening te verifiëren, bijv.
|
|  | [getLocation()](#getLocation--) | De CPU-hostnaam of fysieke locatie van de ondertekening. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | De CPU-hostnaam of fysieke locatie van de ondertekening. |
|
|  | [getReason()](#getReason--) | De reden voor de ondertekening, zoals (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | De reden voor de ondertekening, zoals (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Type van Pdf digitale handtekening. |
|
|  | [setType(int value)](#setType-int-) | Type van Pdf digitale handtekening. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Tijdstempel voor Pdf digitale handtekening. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Tijdstempel voor Pdf digitale handtekening. |
|
|  | [getShowProperties()](#getShowProperties--) | Forceer het tonen/verbergen van handtekeningeigenschappen. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Forceer het tonen/verbergen van handtekeningeigenschappen. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Barcode Signature‑instantie. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Initialiseer Pdf Digital Signature zonder certificaat.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Maak Pdf Digital signature aan met een opgegeven certificaat.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | certificaat | java.security.KeyStore | X509 certificaat. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Informatie verstrekt door de ondertekenaar om een ontvanger in staat te stellen contact op te nemen met de ondertekenaar
om de handtekening te verifiëren, bijv. een telefoonnummer.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Informatie verstrekt door de ondertekenaar om een ontvanger in staat te stellen contact op te nemen met de ondertekenaar
om de handtekening te verifiëren, bijv. een telefoonnummer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


De CPU-hostnaam of fysieke locatie van de ondertekening.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


De CPU-hostnaam of fysieke locatie van de ondertekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


De reden voor de ondertekening, zoals (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


De reden voor de ondertekening, zoals (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Type van Pdf digitale handtekening.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Type van Pdf digitale handtekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Tijdstempel voor Pdf digitale handtekening.
Standaardwaarde is null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Tijdstempel voor Pdf digitale handtekening.
Standaardwaarde is null.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Forceer het tonen/verbergen van handtekeningeigenschappen. In het geval ShowProperties waar is handtekening
veld heeft een vooraf gedefinieerd opmaakformaat
Digitaal ondertekend door {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Datum: {Date} Reden: {
Reden
(#getReason.getReason/#setReason(String).setReason(String))}
Locatie: {
Locatie
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties is standaard waar.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Forceer het tonen/verbergen van handtekeningeigenschappen. In het geval ShowProperties waar is handtekening
veld heeft een vooraf gedefinieerd opmaakformaat
Digitaal ondertekend door {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Datum: {Date} Reden: {
Reden
(#getReason.getReason/#setReason(String).setReason(String))}
Locatie: {
Locatie
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties is standaard waar.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

