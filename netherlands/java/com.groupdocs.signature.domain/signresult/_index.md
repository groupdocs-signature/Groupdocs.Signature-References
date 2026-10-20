---
title: "SignResult"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Resultaat van het ondertekeningsproces voor een document met nieuw aangemaakte handtekeningen."
type: docs
weight: 17
url: /nl/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Resultaat van het ondertekeningsproces voor een document met nieuw aangemaakte handtekeningen.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Retourneert de uitvoeringstijd van het proces in milliseconden |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourneert het totale aantal verwerkte handtekeningen |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourneert de grootte van het bron‑document |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourneert de grootte van het doel‑document |
|
|  | [getSucceeded()](#getSucceeded--) | Lijst van nieuw aangemaakte handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lijst van handtekeningen die niet konden worden aangemaakt. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Retourneert de uitvoeringstijd van het proces in milliseconden


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


Retourneert de grootte van het bron‑document


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Retourneert de grootte van het doel‑document


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lijst van nieuw aangemaakte handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lijst van handtekeningen die niet konden worden aangemaakt.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
