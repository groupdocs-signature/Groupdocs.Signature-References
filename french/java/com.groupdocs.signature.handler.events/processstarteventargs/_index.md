---
title: "ProcessStartEventArgs"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Fournit les données pour l'événement de démarrage du processus de vérification et de recherche de signature"
type: docs
weight: 15
url: /fr/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Fournit des données pour l'événement Start de signature, de vérification et de recherche

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getStarted()](#getStarted--) | Représente le repère temporel du démarrage du processus. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | Représente le repère temporel du démarrage du processus. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Représente la quantité totale de signatures à traiter. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | Représente la quantité totale de signatures à traiter. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Représente le repère temporel du démarrage du processus.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Représente le repère temporel du démarrage du processus.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Représente la quantité totale de signatures à traiter.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Représente la quantité totale de signatures à traiter.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

