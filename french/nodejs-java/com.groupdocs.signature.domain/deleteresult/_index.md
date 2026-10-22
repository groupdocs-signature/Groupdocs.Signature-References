---
title: "DeleteResult"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Résultat de la suppression des signatures du document."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

Résultat de la suppression de la ou des signatures du document.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Renvoie le temps d'exécution du processus en millisecondes. |
| [getTotalSignatures()](#getTotalSignatures--) | Renvoie le nombre total de signatures traitées. |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Renvoie la taille du document source. |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Renvoie la taille du document mis à jour. |
| [getSucceeded()](#getSucceeded--) | Liste des signatures supprimées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Liste des signatures qui n'ont pas été supprimées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Renvoie le temps d'exécution du processus en millisecondes.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Renvoie le nombre total de signatures traitées.

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Renvoie la taille du document source.

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Renvoie la taille du document mis à jour.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste des signatures supprimées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste des signatures qui n'ont pas été supprimées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
