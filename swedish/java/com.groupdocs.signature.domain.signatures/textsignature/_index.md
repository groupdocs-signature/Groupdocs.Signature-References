---
title: "TextSignature"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Innehåller egenskaper för textsignatur."
type: docs
weight: 18
url: /sv/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Innehåller egenskaper för textsignatur.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Initiera TextSignature-objektet med signaturidentifieraren som erhölls efter sökprocessen. |
|
| [TextSignature()](#TextSignature--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getText()](#getText--) | Anger text i signaturen. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Anger text i signaturen. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Anger implementeringen av textsignatur. |
|
|  | [getNative()](#getNative--) | Anger det inbyggda attributet. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Anger det inbyggda attributet. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Skriver över Equals-metoden för att jämföra signaturens egenskaper |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
|  | [deepClone()](#deepClone--) | Klona Text Signature-instans. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Initiera TextSignature-objektet med signaturidentifieraren som erhölls efter sökprocessen.
Denna unika identifierare används för att hitta ytterligare egenskaper för denna signatur från dokumentets signaturinformationslager.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | signatureId | java.lang.String | Unik signaturidentifierare erhållen via signerings- eller sökmetod. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Anger text i signaturen.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Anger text i signaturen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Anger implementeringen av textsignatur.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Anger det inbyggda attributet. Det är true om signaturen är dokumentspecifik.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Anger det inbyggda attributet. Det är true om signaturen är dokumentspecifik.


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


Klona Text Signature-instans.


**Returns:**
java.lang.Object - Returnerar en klonad Text Signature-instans.

