---
title: "ProcessLog"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta i dettagli del processo del documento."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Rappresenta i dettagli del processo del documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDate()](#getDate--) | Ottieni la data e l'ora del processo. |
| [getType()](#getType--) | Ottieni il tipo di processo. |
| [getMessage()](#getMessage--) | Ottieni la descrizione del processo. |
| [getSucceeded()](#getSucceeded--) | Quantità di firme elaborate con successo. |
| [getFailed()](#getFailed--) | Quantità di firme che hanno fallito durante l'elaborazione. |
| [getSignatures()](#getSignatures--) | L'elenco delle firme elaborate con successo. |
### getDate() {#getDate--}
```
public final Date getDate()
```


Ottieni la data e l'ora del processo.

**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Ottieni il tipo di processo.

**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Ottieni la descrizione del processo.

**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Quantità di firme elaborate con successo.

**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Quantità di firme che hanno fallito durante l'elaborazione.

**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


L'elenco delle firme elaborate con successo.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
