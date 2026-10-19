---
title: "DocumentResultSignature"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Résultat du traitement du processus de signature de document d'archive pour un document avec des signatures nouvellement créées."
type: docs
weight: 13
url: /fr/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

Résultat du traitement du processus de signature de document d'archive pour un document avec des signatures nouvellement créées.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFileName()](#getFileName--) | Nom du fichier du document |
|
|  | [getProcessingTime()](#getProcessingTime--) | Retourne le temps d'exécution du processus en millisecondes |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourne le nombre total de signatures traitées |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourne la taille du document source |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Retourne la taille du document de destination |
|
|  | [getSucceeded()](#getSucceeded--) | Liste des signatures traitées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Liste des signatures qui ont échoué pendant le processus [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | si le document a été traité avec une erreur, cette propriété contiendra le message d'erreur |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Nom du fichier du document


**Returns:**
java.lang.String
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


Liste des signatures traitées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste des signatures qui ont échoué pendant le processus [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


si le document a été traité avec une erreur, cette propriété contiendra le message d'erreur


**Returns:**
java.lang.String
