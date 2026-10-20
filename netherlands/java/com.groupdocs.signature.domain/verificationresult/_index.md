---
title: "VerificationResult"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Instantie om resultaten van het verificatieproces bij te houden."
type: docs
weight: 20
url: /nl/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instantie om resultaten van het verificatieproces bij te houden.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Retourneert de uitvoeringstijd van het proces in milliseconden. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourneert het totale aantal verwerkte handtekeningen |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourneert de grootte van het brondocument in bytes |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourneert de grootte van het bestemmingsdocument. |
|
|  | [getSucceeded()](#getSucceeded--) | Lijst van succesvol geverifieerde handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lijst van handtekeningen waarvoor het verificatieproces is mislukt. |
|
|  | [isValid()](#isValid--) | Retourneert true als het verificatieproces succesvol was, anders false. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Retourneert true als het verificatieproces succesvol was, anders false. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Retourneert de uitvoeringstijd van het proces in milliseconden.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Retourneert het totale aantal verwerkte handtekeningen


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Retourneert de grootte van het brondocument in bytes


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Retourneert de grootte van het bestemmingsdocument. Voor verificatie bevat deze variabele altijd nul.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lijst van succesvol geverifieerde handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
Momenteel wordt deze eigenschap niet ondersteund.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lijst van handtekeningen waarvoor het verificatieproces is mislukt.
Momenteel wordt deze eigenschap niet ondersteund.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Retourneert true als het verificatieproces succesvol was, anders false.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Retourneert true als het verificatieproces succesvol was, anders false.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

