---
title: "VerificationResult"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Instans för att behålla resultat av verifieringsprocessen."
type: docs
weight: 20
url: /sv/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instans för att behålla resultat av verifieringsprocessen.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Returnerar processens exekveringstid i millisekunder. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Returnerar det totala antalet bearbetade signaturer |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Returnerar källdokumentets storlek i byte |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Returnerar destinationsdokumentets storlek. |
|
|  | [getSucceeded()](#getSucceeded--) | Lista över framgångsrikt verifierade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista över signaturer som misslyckades med verifieringsprocessen. |
|
|  | [isValid()](#isValid--) | Returnerar true om verifieringsprocessen var framgångsrik, annars false. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Returnerar true om verifieringsprocessen var framgångsrik, annars false. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returnerar processens exekveringstid i millisekunder.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Returnerar det totala antalet bearbetade signaturer


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Returnerar källdokumentets storlek i byte


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returnerar destinationsdokumentets storlek. För verifiering innehåller denna variabel alltid noll.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista över framgångsrikt verifierade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
Denna egenskap stöds för närvarande inte.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista över signaturer som misslyckades med verifieringsprocessen.
Denna egenskap stöds för närvarande inte.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Returnerar true om verifieringsprocessen var framgångsrik, annars false.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Returnerar true om verifieringsprocessen var framgångsrik, annars false.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

