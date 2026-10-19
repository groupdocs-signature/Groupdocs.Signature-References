---
title: "UpdateResult"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Résultat de la modification des signatures dans le document."
type: docs
weight: 19
url: /fr/java/com.groupdocs.signature.domain/updateresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class UpdateResult implements IResult
```

Résultat de la modification des signatures dans le document.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Retourne le temps d'exécution du processus en millisecondes |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourne le nombre total de signatures traitées |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourne la taille du document source |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourne la taille du document de destination |
|
|  | [getSucceeded()](#getSucceeded--) | Liste des signatures modifiées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Liste des signatures qui n'ont pas été mises à jour [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Retourne le temps d'exécution du processus en millisecondes


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Retourne le nombre total de signatures traitées


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Retourne la taille du document source


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Retourne la taille du document de destination


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste des signatures modifiées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste des signatures qui n'ont pas été mises à jour [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
