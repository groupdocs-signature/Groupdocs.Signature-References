---
title: "SearchResult"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Résultat de la recherche de signatures dans le document spécifié."
type: docs
weight: 16
url: /fr/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Résultat de la recherche de signatures dans le document spécifié.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Renvoie le temps d'exécution du processus de recherche en millisecondes. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Renvoie le nombre total de signatures traitées par le processus de recherche |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Retourne la taille du document source |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Renvoie la taille du document de destination. |
|
|  | [getSucceeded()](#getSucceeded--) | Liste des signatures trouvées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Liste des signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) qui ont échoué lors du processus de recherche selon les critères de recherche. |
|
|  | [getSignatures()](#getSignatures--) | Liste des signatures détectées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Fournit la conversion en une liste fortement typée de signatures. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Renvoie le temps d'exécution du processus de recherche en millisecondes.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Renvoie le nombre total de signatures traitées par le processus de recherche


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


Renvoie la taille du document de destination. Pour la méthode Search, elle renvoie toujours 0.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Liste des signatures trouvées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Cette liste sera toujours égale à
Signatures
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) propriété.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Liste des signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) qui ont échoué lors du processus de recherche selon les critères de recherche.
Non pris en charge dans la version actuelle.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Liste des signatures détectées [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Fournit la conversion en une liste fortement typée de signatures.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Renvoie la liste du type de signature donné.


T
: Le type de signatures dans la liste.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

