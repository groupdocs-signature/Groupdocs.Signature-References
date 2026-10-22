---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Risultato dell'elaborazione del processo di firma del documento archivio per un documento con firme appena create."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Risultato dell'elaborazione del processo di firma del documento archivio per un documento con firme appena create.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileName()](#getFileName--) | Nome file del documento |
| [getProcessingTime()](#getProcessingTime--) | Restituisce il tempo di esecuzione del processo in millisecondi |
| [getTotalSignatures()](#getTotalSignatures--) | Restituisce il totale delle firme elaborate |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Restituisce la dimensione del documento di origine |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Restituisce la dimensione del documento di destinazione |
| [getSucceeded()](#getSucceeded--) | Elenco delle firme elaborate con successo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Elenco delle firme che hanno fallito durante il processo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getErrorMessage()](#getErrorMessage--) | Se il documento è stato elaborato con errore, questa proprietà conterrà il messaggio di errore |
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Nome file del documento

**Returns:**
java.lang.String
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


Elenco delle firme elaborate con successo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Elenco delle firme che hanno fallito durante il processo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


Se il documento è stato elaborato con errore, questa proprietà conterrà il messaggio di errore

**Returns:**
java.lang.String
