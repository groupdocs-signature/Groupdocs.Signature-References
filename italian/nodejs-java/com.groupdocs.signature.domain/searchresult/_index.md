---
title: "SearchResult"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Risultato della ricerca di firme nel documento specificato."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Risultato della ricerca di firme nel documento specificato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Restituisce il tempo di esecuzione del processo di ricerca in millisecondi. |
| [getTotalSignatures()](#getTotalSignatures--) | Restituisce il totale delle firme elaborate dal processo di ricerca |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Restituisce la dimensione del documento di origine |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Restituisce la dimensione del documento di destinazione. |
| [getSucceeded()](#getSucceeded--) | Elenco delle firme trovate [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Elenco delle firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) che hanno fallito il processo di ricerca per i criteri di ricerca. |
| [getSignatures()](#getSignatures--) | Elenco delle firme rilevate [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Fornisce la conversione in un elenco tipizzato di firme. |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Restituisce il tempo di esecuzione del processo di ricerca in millisecondi.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Restituisce il totale delle firme elaborate dal processo di ricerca

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Restituisce la dimensione del documento di origine

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Restituisce la dimensione del documento di destinazione. Per il metodo Search restituisce sempre 0.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Elenco delle firme trovate [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Questo elenco sarà sempre uguale alla proprietà Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Elenco delle firme [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) che hanno fallito il processo di ricerca per i criteri di ricerca. Non supportato nella versione corrente.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Elenco delle firme rilevate [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Fornisce la conversione in un elenco tipizzato di firme.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Restituisce l'elenco del tipo di firma specificato.

T : Il tipo di firme nell'elenco.
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

