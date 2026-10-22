---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Fournit des données pour l'événement OnProgress des processus de vérification et de recherche de signatures."
type: docs
weight: 13
url: /fr/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Fournit des données pour l'événement OnProgress des processus de signature, de vérification et de recherche.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getProgress()](#getProgress--) | Représente la progression en pourcentage. |
| [setProgress(int value)](#setProgress-int-) | Représente la progression en pourcentage. |
| [getTicks()](#getTicks--) | Représente le temps écoulé en millisecondes depuis l'événement de démarrage du processus. |
| [setTicks(long value)](#setTicks-long-) | Représente le temps écoulé en millisecondes depuis l'événement de démarrage du processus. |
| [getProcessedSignatures()](#getProcessedSignatures--) | Représente la quantité de signatures traitées. |
| [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Représente la quantité de signatures traitées. |
| [getCancel()](#getCancel--) | Indique si le processus doit être annulé. |
| [setCancel(boolean value)](#setCancel-boolean-) | Indique si le processus doit être annulé. |
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Représente la progression en pourcentage. La plage de valeurs va de 0 à 100.

**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Représente la progression en pourcentage. La plage de valeurs va de 0 à 100.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Représente le temps écoulé en millisecondes depuis l'événement de démarrage du processus.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Représente le temps écoulé en millisecondes depuis l'événement de démarrage du processus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Représente la quantité de signatures traitées.

**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Représente la quantité de signatures traitées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Indique si le processus doit être annulé.

**Returns:**
booléen
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Indique si le processus doit être annulé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

