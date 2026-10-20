---
title: "DigitalSignatureAppearance"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Beschrijft de weergave van de handtekeninglijn voor een digitale handtekening."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Beschrijft de weergave van de handtekeninglijn voor een digitale handtekening.
Een handtekeningregel kan slechts voor één digitale handtekening worden toegepast.
Handtekeningregel staat altijd op de eerste pagina.
Deze functie kan nuttig zijn voor .docx-, .doc-, .odt- en .xlsx-bestandsformaten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Maakt een Signature Line Appearance-object aan. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Maakt een Signature Line Appearance met opgegeven waarden (ondertekenaar, titel, e‑mail). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSigner()](#getSigner--) | Haalt de naam van de ondertekenaar op voor de handtekeningregel of stelt deze in. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | Haalt de naam van de ondertekenaar op voor de handtekeningregel of stelt deze in. |
|
|  | [getTitle()](#getTitle--) | Haalt een titel op voor de handtekeningregel of stelt deze in. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | Haalt een titel op voor de handtekeningregel of stelt deze in. |
|
|  | [getEmail()](#getEmail--) | Haalt een e‑mail op die in de handtekeningregel wordt weergegeven of stelt deze in. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | Haalt een e‑mail op die in de handtekeningregel wordt weergegeven of stelt deze in. |
|
|  | [toString()](#toString--) | Overschrijf tekenreeksconversie. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Maakt een Signature Line Appearance-object aan.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Maakt een Signature Line Appearance met opgegeven waarden (ondertekenaar, titel, e‑mail).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | ondertekenaar | java.lang.String | Naam van ondertekenaar. |
|
|  | title | java.lang.String | Handtekeningtitel. |
|
|  | e‑mail | java.lang.String | E‑mail van auteur. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Haalt de naam van de ondertekenaar op voor de handtekeningregel of stelt deze in.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Haalt de naam van de ondertekenaar op voor de handtekeningregel of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Haalt een titel op voor de handtekeningregel of stelt deze in.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Haalt een titel op voor de handtekeningregel of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Haalt een e‑mail op die in de handtekeningregel wordt weergegeven of stelt deze in.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Haalt een e‑mail op die in de handtekeningregel wordt weergegeven of stelt deze in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Overschrijf tekenreeksconversie.


**Returns:**
java.lang.String -
