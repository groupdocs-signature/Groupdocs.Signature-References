---
title: "SearchResult"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Resultaat van het zoeken naar handtekeningen in het opgegeven document."
type: docs
weight: 16
url: /nl/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Resultaat van het zoeken naar handtekeningen in het opgegeven document.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Retourneert de uitvoeringstijd van het zoekproces in milliseconden. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourneert het totale aantal verwerkte handtekeningen door het zoekproces |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourneert de grootte van het bron‑document |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourneert de grootte van het bestemmingsdocument. |
|
|  | [getSucceeded()](#getSucceeded--) | Lijst met gevonden handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lijst met handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) die het zoekproces niet hebben doorstaan volgens de zoekcriteria. |
|
|  | [getSignatures()](#getSignatures--) | Lijst van gedetecteerde handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Biedt conversie naar een sterk getypeerde lijst van handtekeningen. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Retourneert de uitvoeringstijd van het zoekproces in milliseconden.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Retourneert het totale aantal verwerkte handtekeningen door het zoekproces


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


Retourneert de grootte van het bestemmingsdocument. Voor de Search-methode retourneert het altijd 0.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lijst van gevonden handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Deze lijst zal altijd gelijk zijn aan
Handtekeningen
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) eigenschap.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lijst met handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) die het zoekproces niet hebben doorstaan volgens de zoekcriteria.
Niet ondersteund in de huidige versie.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Lijst van gedetecteerde handtekeningen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Biedt conversie naar een sterk getypeerde lijst van handtekeningen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Retourneert een lijst van het opgegeven handtekeningtype.


T
: Het type handtekeningen in de lijst.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

