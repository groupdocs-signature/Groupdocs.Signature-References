---
title: "SignResult"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Risultato del processo di firma del documento con firme appena create."
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

Risultato del processo di firma del documento con firme appena create.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Restituisce il tempo di esecuzione del processo in millisecondi |
| [getTotalSignatures()](#getTotalSignatures--) | Restituisce il totale delle firme elaborate |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Restituisce la dimensione del documento di origine |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Restituisce la dimensione del documento di destinazione |
| [getSucceeded()](#getSucceeded--) | Elenco delle firme appena create [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Elenco delle firme che non sono state create. |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Restituisce il tempo di esecuzione del processo in millisecondi

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Restituisce il totale delle firme elaborate

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


Restituisce la dimensione del documento di destinazione

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Elenco delle firme appena create [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Elenco delle firme che non sono state create.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
