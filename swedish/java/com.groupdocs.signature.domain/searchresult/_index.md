---
title: "SearchResult"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Resultat av sökning efter signaturer i angivet dokument."
type: docs
weight: 16
url: /sv/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Resultat av sökning efter signaturer i angivet dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Returnerar exekveringstiden för sökprocessen i millisekunder. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Returnerar det totala antalet bearbetade signaturer av sökprocessen. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Returnerar källdokumentets storlek |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Returnerar destinationsdokumentets storlek. |
|
|  | [getSucceeded()](#getSucceeded--) | Lista över hittade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Lista över signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) som misslyckades med sökprocessen enligt sökkriterier. |
|
|  | [getSignatures()](#getSignatures--) | Lista över upptäckta signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Tillhandahåller konvertering till en starkt typad lista av signaturer. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returnerar exekveringstiden för sökprocessen i millisekunder.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Returnerar det totala antalet bearbetade signaturer av sökprocessen.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Returnerar källdokumentets storlek


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returnerar destinationsdokumentets storlek. För Search‑metoden returneras alltid 0.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Lista över hittade signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Denna lista kommer alltid att vara lika med
Signaturer
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) egenskap.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Lista över signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) som misslyckades med sökprocessen enligt sökkriterier.
Stöds inte i aktuell version.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Lista över upptäckta signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Tillhandahåller konvertering till en starkt typad lista av signaturer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Returnerar lista av given signaturtyp.


T
: Typen av signaturer i listan.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

