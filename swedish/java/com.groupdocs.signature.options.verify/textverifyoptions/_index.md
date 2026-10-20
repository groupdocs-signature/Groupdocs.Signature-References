---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Behåller alternativ för att verifiera dokumentets Text-signatur."
type: docs
weight: 14
url: /sv/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Behåller alternativ för att verifiera dokumentets Text-signatur.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | Initierar en ny instans av TextVerifyOptions med standardvärden. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Initierar en ny instans av TextVerifyOptions med verifieringstext. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Initierar en ny instans av TextVerifyOptions med Text-egenskapen att verifiera och signaturimplementering. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Ange signaturtext om den ska verifieras. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Ange signaturtext om den ska verifieras. |
|
|  | [getMatchType()](#getMatchType--) | Hämtar eller anger verifiering av textmatchningstyp. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Hämtar eller anger verifiering av textmatchningstyp. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Typ av signatur som ska verifieras. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Typ av signatur som ska verifieras. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Hämtar eller anger titeln på formulärfältet för att verifiera det. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Hämtar eller anger titeln på formulärfältet för att verifiera det. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Hämtar eller anger typen av formulärfält för att verifiera det. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Hämtar eller anger typen av formulärfält för att verifiera det. |
|
|  | [getSignatureID()](#getSignatureID--) | Ange textsignatur-ID större än noll om den ska verifieras. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Ange textsignatur-ID större än noll om den ska verifieras. |
|
|  | [toString()](#toString--) | Åsidosätter konvertering till sträng. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Initierar en ny instans av TextVerifyOptions med standardvärden.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Initierar en ny instans av TextVerifyOptions med verifieringstext.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Text att verifiera |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Initierar en ny instans av TextVerifyOptions med Text-egenskapen att verifiera och signaturimplementering.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | text | java.lang.String | Text att verifiera. |
|
|  | implementering | int | Typ av signaturimplementering. |
|

### getText() {#getText--}
```
public final String getText()
```


Ange signaturtext om den ska verifieras.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Ange signaturtext om den ska verifieras.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Typ av signatur som ska verifieras.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Typ av signatur som ska verifieras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Hämtar eller anger titeln på formulärfältet för att verifiera det.
Om detta egenskapsvärde är satt kommer texten endast att hittas i textformulärfält.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Hämtar eller anger titeln på formulärfältet för att verifiera det.
Om detta egenskapsvärde är satt kommer texten endast att hittas i textformulärfält.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Hämtar eller anger typen av formulärfält för att verifiera det.
Om detta egenskapsvärde är satt kommer texten endast att hittas i textformulärfält.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Hämtar eller anger typen av formulärfält för att verifiera det.
Om detta egenskapsvärde är satt kommer texten endast att hittas i textformulärfält.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Ange textsignatur-ID större än noll om den ska verifieras. Denna egenskap stöds endast för PDF-dokument.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Ange textsignatur-ID större än noll om den ska verifieras. Denna egenskap stöds endast för PDF-dokument.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätter konvertering till sträng.


**Returns:**
java.lang.String -
