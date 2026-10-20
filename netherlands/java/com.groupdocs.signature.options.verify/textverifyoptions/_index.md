---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat opties om de teksthandtekening van een document te verifiëren."
type: docs
weight: 14
url: /nl/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Bevat opties om de teksthandtekening van een document te verifiëren.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van TextVerifyOptions met verificatietekst. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Initialiseert een nieuw exemplaar van TextVerifyOptions met de Text-eigenschap om te verifiëren en handtekeningimplementatie. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Geef de handtekeningtekst op als deze moet worden geverifieerd. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Geef de handtekeningtekst op als deze moet worden geverifieerd. |
|
|  | [getMatchType()](#getMatchType--) | Haalt op of stelt verificatie van tekstovereenkomsttype in. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Haalt op of stelt verificatie van tekstovereenkomsttype in. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Type handtekening dat moet worden geverifieerd. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Type handtekening dat moet worden geverifieerd. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Haalt de titel van het formulierveld op of stelt deze in om het te verifiëren. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Haalt de titel van het formulierveld op of stelt deze in om het te verifiëren. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | Haalt het type van het formulierveld op of stelt dit in om het te verifiëren. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Haalt het type van het formulierveld op of stelt dit in om het te verifiëren. |
|
|  | [getSignatureID()](#getSignatureID--) | Geef een Teksthandtekening-ID groter dan nul op als deze moet worden geverifieerd. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | Geef een Teksthandtekening-ID groter dan nul op als deze moet worden geverifieerd. |
|
|  | [toString()](#toString--) | Overschrijft conversie naar string. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Initialiseert een nieuw exemplaar van TextVerifyOptions met standaardwaarden.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Initialiseert een nieuw exemplaar van TextVerifyOptions met verificatietekst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Te verifiëren tekst |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Initialiseert een nieuw exemplaar van TextVerifyOptions met de Text-eigenschap om te verifiëren en handtekeningimplementatie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | tekst | java.lang.String | Te verifiëren tekst. |
|
|  | implementatie | int | Handtekeningimplementatietype. |
|

### getText() {#getText--}
```
public final String getText()
```


Geef de handtekeningtekst op als deze moet worden geverifieerd.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Geef de handtekeningtekst op als deze moet worden geverifieerd.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Type handtekening dat moet worden geverifieerd.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Type handtekening dat moet worden geverifieerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Haalt de titel van het formulierveld op of stelt deze in om het te verifiëren.
Als deze eigenschap is ingesteld, wordt tekst alleen gevonden in tekstformuliervelden.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Haalt de titel van het formulierveld op of stelt deze in om het te verifiëren.
Als deze eigenschap is ingesteld, wordt tekst alleen gevonden in tekstformuliervelden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Haalt het type van het formulierveld op of stelt dit in om het te verifiëren.
Als deze eigenschap is ingesteld, wordt tekst alleen gevonden in tekstformuliervelden.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Haalt het type van het formulierveld op of stelt dit in om het te verifiëren.
Als deze eigenschap is ingesteld, wordt tekst alleen gevonden in tekstformuliervelden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Geef een Teksthandtekening-ID groter dan nul op als deze moet worden geverifieerd. Deze eigenschap wordt alleen ondersteund voor PDF-documenten.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Geef een Teksthandtekening-ID groter dan nul op als deze moet worden geverifieerd. Deze eigenschap wordt alleen ondersteund voor PDF-documenten.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijft conversie naar string.


**Returns:**
java.lang.String -
