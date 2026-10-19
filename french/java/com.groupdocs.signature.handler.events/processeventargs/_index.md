---
title: "ProcessEventArgs"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Fournit des données pour différents événements de vérification de signature et de processus de recherche."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

Fournit des données pour différents événements des processus de signature, de vérification et de recherche.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFilePath()](#getFilePath--) | Représente le nom de fichier de traitement du document. |
|
|  | [setFilePath(String value)](#setFilePath-java.lang.String-) | Représente le nom de fichier de traitement du document. |
|
|  | [getStatus()](#getStatus--) | Indique l'état actuel du processus. |
|
|  | [setStatus(int value)](#setStatus-int-) | Indique l'état actuel du processus. |
|
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Représente le nom de fichier de traitement du document.


**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


Représente le nom de fichier de traitement du document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Indique l'état actuel du processus.


**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Indique l'état actuel du processus.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

