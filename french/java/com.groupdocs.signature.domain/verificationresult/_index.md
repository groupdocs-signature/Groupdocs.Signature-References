---
title: "VerificationResult"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Instance pour conserver les résultats du processus de vérification."
type: docs
weight: 20
url: /fr/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

Instance pour conserver les résultats du processus de vérification.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Renvoie le temps d'exécution du processus en millisecondes. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Retourne le nombre total de signatures traitées |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Renvoie la taille du document source en octets |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Renvoie la taille du document de destination. |
|
|  | [getSucceeded()](#getSucceeded--) | Liste des signatures vérifiées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [isValid()](#isValid--) | Renvoie true si le processus de vérification a réussi, sinon false. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | Renvoie true si le processus de vérification a réussi, sinon false. |
|
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


Retourne le nombre total de signatures traitées


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Renvoie la taille du document source en octets


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Renvoie la taille du document de destination. Pour la vérification, cette variable contient toujours zéro.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste des signatures vérifiées avec succès [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
Actuellement, cette propriété n'est pas prise en charge.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


Renvoie true si le processus de vérification a réussi, sinon false.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Renvoie true si le processus de vérification a réussi, sinon false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

