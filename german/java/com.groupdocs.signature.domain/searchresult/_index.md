---
title: "SearchResult"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Ergebnis der Suche nach Signaturen im angegebenen Dokument."
type: docs
weight: 16
url: /de/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Ergebnis der Suche nach Signaturen im angegebenen Dokument.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Gibt die Ausführungszeit des Suchvorgangs in Millisekunden zurück. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Gibt die insgesamt vom Suchvorgang verarbeiteten Signaturen zurück |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Gibt die Größe des Quelldokuments zurück |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Gibt die Größe des Zieldokuments zurück. |
|
|  | [getSucceeded()](#getSucceeded--) | Liste gefundener Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), die den Suchvorgang nach Suchkriterien nicht bestanden haben. |
|
|  | [getSignatures()](#getSignatures--) | Liste erkannter Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Stellt die Konvertierung in eine stark typisierte Signaturliste bereit. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Gibt die Ausführungszeit des Suchvorgangs in Millisekunden zurück.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Gibt die insgesamt vom Suchvorgang verarbeiteten Signaturen zurück


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Gibt die Größe des Quelldokuments zurück


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Gibt die Größe des Zieldokuments zurück. Für die Search-Methode wird immer 0 zurückgegeben.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste gefundener Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Diese Liste wird immer gleich sein zu
Signaturen
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) Eigenschaft.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste von Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), die den Suchvorgang nach Suchkriterien nicht bestanden haben.
In der aktuellen Version nicht unterstützt.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Liste erkannter Signaturen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Stellt die Konvertierung in eine stark typisierte Signaturliste bereit.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Gibt eine Liste des angegebenen Signaturtyps zurück.


T
: Der Typ der Signaturen in der Liste.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

