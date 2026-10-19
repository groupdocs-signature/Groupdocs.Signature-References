---
title: "ProcessCompleteEventArgs"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Fournit des données sur l'événement complet de vérification de signature et de processus de recherche."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Fournit des données sur l'événement complet de signature, de vérification et de recherche.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | Représente le repère temporel de l'achèvement du processus. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | Représente le repère temporel de l'achèvement du processus. |
|
|  | [getTicks()](#getTicks--) | Représente le temps en millisecondes écoulé depuis l'événement de démarrage du processus. |
|
|  | [setTicks(long value)](#setTicks-long-) | Représente le temps en millisecondes écoulé depuis l'événement de démarrage du processus. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Représente la quantité totale de signatures traitées. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Représente la quantité totale de signatures traitées. |
|
|  | [getCanceled()](#getCanceled--) | Indique si le processus a été annulé. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Représente le repère temporel de l'achèvement du processus.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Représente le repère temporel de l'achèvement du processus.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Représente le temps en millisecondes écoulé depuis l'événement de démarrage du processus.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Représente le temps en millisecondes écoulé depuis l'événement de démarrage du processus.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Représente la quantité totale de signatures traitées.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Représente la quantité totale de signatures traitées.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Indique si le processus a été annulé.


**Returns:**
boolean
