---
title: "DeleteResult"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Resultaat van het verwijderen van handtekeningen uit het document."
type: docs
weight: 12
url: /nl/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Resultaat van het verwijderen van handtekening(en) uit het document.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Retourneert de uitvoeringstijd van het proces in milliseconden. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourneert het totale aantal verwerkte handtekeningen. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourneert de grootte van het brondocument. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourneert de bijgewerkte documentgrootte. |
|
|  | [getSucceeded()](#getSucceeded--) | Lijst van succesvol verwijderde handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lijst van handtekeningen die niet zijn verwijderd [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


Retourneert het totale aantal verwerkte handtekeningen.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Retourneert de grootte van het brondocument.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Retourneert de bijgewerkte documentgrootte.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lijst van succesvol verwijderde handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lijst van handtekeningen die niet zijn verwijderd [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
