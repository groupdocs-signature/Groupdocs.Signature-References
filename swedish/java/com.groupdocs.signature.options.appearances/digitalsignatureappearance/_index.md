---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Beskriver utseendet på signaturlinjen för digital signatur."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Beskriver utseendet på signaturlinjen för digital signatur.
En signaturlinje kan endast tillämpas för en digital signatur.
Signaturlinjen är alltid på den första sidan.
Denna funktion kan vara användbar för filformaten .docx, .doc, .odt och .xlsx.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Skapar ett objekt för signaturlinjens utseende. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Skapar signaturlinjens utseende med angivna värden (signer, title, email). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSigner()](#getSigner--) | Hämtar eller anger signatörens namn för signaturlinjen. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | Hämtar eller anger signatörens namn för signaturlinjen. |
|
|  | [getTitle()](#getTitle--) | Hämtar eller anger en titel för signaturlinjen. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Hämtar eller anger en titel för signaturlinjen. |
|
|  | [getEmail()](#getEmail--) | Hämtar eller anger en e‑post som kommer att visas i signaturlinjen. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | Hämtar eller anger en e‑post som kommer att visas i signaturlinjen. |
|
|  | [toString()](#toString--) | Åsidosätt strängkonvertering. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Skapar ett objekt för signaturlinjens utseende.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Skapar signaturlinjens utseende med angivna värden (signer, title, email).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signer | java.lang.String | Signatörens namn. |
|
|  | titel | java.lang.String | Signaturtitel. |
|
|  | email | java.lang.String | Författarens e‑post. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Hämtar eller anger signatörens namn för signaturlinjen.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Hämtar eller anger signatörens namn för signaturlinjen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Hämtar eller anger en titel för signaturlinjen.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Hämtar eller anger en titel för signaturlinjen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Hämtar eller anger en e‑post som kommer att visas i signaturlinjen.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Hämtar eller anger en e‑post som kommer att visas i signaturlinjen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Åsidosätt strängkonvertering.


**Returns:**
java.lang.String -
