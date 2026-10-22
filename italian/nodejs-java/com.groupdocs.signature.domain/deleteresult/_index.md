---
title: "DeleteResult"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Risultato dell'eliminazione delle firme dal documento."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Risultato dell'eliminazione della/e firma/e dal documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Restituisce il tempo di esecuzione del processo in millisecondi. |
| [getTotalSignatures()](#getTotalSignatures--) | Restituisce il totale delle firme elaborate. |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Restituisce la dimensione del documento sorgente. |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Restituisce la dimensione del documento aggiornato. |
| [getSucceeded()](#getSucceeded--) | Elenco delle firme eliminate con successo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Elenco delle firme non eliminate [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Restituisce il tempo di esecuzione del processo in millisecondi.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Restituisce il totale delle firme elaborate.

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Restituisce la dimensione del documento sorgente.

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Restituisce la dimensione del documento aggiornato.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Elenco delle firme eliminate con successo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Elenco delle firme non eliminate [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
