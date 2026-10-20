---
title: "TextSignature"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Bevat eigenschappen van teksthandtekening."
type: docs
weight: 18
url: /nl/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Bevat eigenschappen van teksthandtekening.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Initialiseer TextSignature-object met handtekening‑identificatie die is verkregen na het zoekproces. |
|
| [TextSignature()](#TextSignature--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getText()](#getText--) | Specificeert tekst in de handtekening. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Specificeert tekst in de handtekening. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Specificeert de implementatie van de teksthandtekening. |
|
|  | [getNative()](#getNative--) | Specificeert het native‑attribuut. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Specificeert het native‑attribuut. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Overschrijft de Equals-methode om handtekeningeigenschappen te vergelijken |
|
|  | [hashCode()](#hashCode--) | Overschrijft de GetHashCode‑methode |
|
|  | [deepClone()](#deepClone--) | Kloon Text Signature‑instantie. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Initialiseer TextSignature-object met handtekening‑identificatie die is verkregen na het zoekproces.
Deze unieke identificatie wordt gebruikt om extra eigenschappen voor deze handtekening te vinden vanuit de documenthandtekening‑informatielaag.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unieke handtekening‑identificatie verkregen via ondertekenings‑ of zoekmethode. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Specificeert tekst in de handtekening.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specificeert tekst in de handtekening.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Specificeert de implementatie van de teksthandtekening.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Specificeert het native‑attribuut. Het is waar als de handtekening documentspecifiek is.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Specificeert het native‑attribuut. Het is waar als de handtekening documentspecifiek is.


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


Kloon Text Signature‑instantie.


**Returns:**
java.lang.Object - Retourneert een gekloonde Text Signature‑instantie.

