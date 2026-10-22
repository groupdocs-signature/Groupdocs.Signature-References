---
title: "VerificationResult"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Istanza per conservare i risultati del processo di verifica."
type: docs
weight: 20
url: /it/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Istanza per conservare i risultati del processo di verifica.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Restituisce il tempo di esecuzione del processo in millisecondi. |
| [getTotalSignatures()](#getTotalSignatures--) | Restituisce il totale delle firme elaborate |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Restituisce la dimensione del documento sorgente in byte |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Restituisce la dimensione del documento di destinazione. |
| [getSucceeded()](#getSucceeded--) | Elenco delle firme verificate con successo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [isValid()](#isValid--) | Restituisce true se il processo di verifica è stato completato con successo, altrimenti false. |
| [setValid(boolean value)](#setValid-boolean-) | Restituisce true se il processo di verifica è stato completato con successo, altrimenti false. |
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


Restituisce il totale delle firme elaborate

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Restituisce la dimensione del documento sorgente in byte

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Restituisce la dimensione del documento di destinazione. Per la verifica questa variabile contiene sempre zero.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Elenco delle firme verificate con successo [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Attualmente questa proprietà non è supportata.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Restituisce true se il processo di verifica è stato completato con successo, altrimenti false.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Restituisce true se il processo di verifica è stato completato con successo, altrimenti false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

