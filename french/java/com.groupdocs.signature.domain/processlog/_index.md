---
title: "ProcessLog"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente les détails du processus de document."
type: docs
weight: 15
url: /fr/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

Représente les détails du processus de document.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDate()](#getDate--) | Obtenez la date et l'heure du processus. |
|
|  | [getType()](#getType--) | Obtenez le type du processus. |
|
|  | [getMessage()](#getMessage--) | Obtenez la description du processus. |
|
|  | [getSucceeded()](#getSucceeded--) | Quantité de signatures traitées avec succès. |
|
|  | [getFailed()](#getFailed--) | Quantité de signatures qui ont échoué pendant le traitement. |
|
|  | [getSignatures()](#getSignatures--) | La liste des signatures traitées avec succès. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


Obtenez la date et l'heure du processus.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


Obtenez le type du processus.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


Obtenez la description du processus.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


Quantité de signatures traitées avec succès.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


Quantité de signatures qui ont échoué pendant le traitement.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


La liste des signatures traitées avec succès.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
