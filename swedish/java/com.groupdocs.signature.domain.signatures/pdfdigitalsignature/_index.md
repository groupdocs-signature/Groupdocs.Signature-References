---
title: "PdfDigitalSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för PDF‑digital signatur."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Innehåller egenskaper för PDF‑digital signatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | Initiera Pdf Digital Signature utan certifikat. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Skapa Pdf Digital signature med angivet certifikat. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | Information som tillhandahålls av undertecknaren för att möjliggöra för mottagaren att kontakta undertecknaren |
för att verifiera signaturen, t.ex.
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Information som tillhandahålls av undertecknaren för att möjliggöra för mottagaren att kontakta undertecknaren |
för att verifiera signaturen, t.ex.
|
|  | [getLocation()](#getLocation--) | CPU-värdnamnet eller den fysiska platsen för signeringen. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | CPU-värdnamnet eller den fysiska platsen för signeringen. |
|
|  | [getReason()](#getReason--) | Anledningen till signeringen, till exempel (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | Anledningen till signeringen, till exempel (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Typ av PDF-digital signatur. |
|
|  | [setType(int value)](#setType-int-) | Typ av PDF-digital signatur. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Tidsstämpel för PDF-digital signatur. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Tidsstämpel för PDF-digital signatur. |
|
|  | [getShowProperties()](#getShowProperties--) | Tvinga att visa/dölja signaturens egenskaper. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | Tvinga att visa/dölja signaturens egenskaper. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Barcode Signature-instans. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Initiera Pdf Digital Signature utan certifikat.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Skapa Pdf Digital signature med angivet certifikat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | certifikat | java.security.KeyStore | X509-certifikat. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Information som tillhandahålls av undertecknaren för att möjliggöra för mottagaren att kontakta undertecknaren
för att verifiera signaturen, t.ex. ett telefonnummer.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Information som tillhandahålls av undertecknaren för att möjliggöra för mottagaren att kontakta undertecknaren
för att verifiera signaturen, t.ex. ett telefonnummer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


CPU-värdnamnet eller den fysiska platsen för signeringen.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


CPU-värdnamnet eller den fysiska platsen för signeringen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Anledningen till signeringen, till exempel (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Anledningen till signeringen, till exempel (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Typ av PDF-digital signatur.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Typ av PDF-digital signatur.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Tidsstämpel för PDF-digital signatur.
Standardvärdet är null.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Tidsstämpel för PDF-digital signatur.
Standardvärdet är null.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Tvinga att visa/dölja signaturens egenskaper. Om ShowProperties är true signatur
fältet har ett fördefinierat format för utseende
Digitalt signerat av {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Datum: {Date} Orsak: {
Orsak
(#getReason.getReason/#setReason(String).setReason(String))}
Plats: {
Plats
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties är true som standard.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Tvinga att visa/dölja signaturens egenskaper. Om ShowProperties är true signatur
fältet har ett fördefinierat format för utseende
Digitalt signerat av {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} Datum: {Date} Orsak: {
Orsak
(#getReason.getReason/#setReason(String).setReason(String))}
Plats: {
Plats
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties är true som standard.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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

