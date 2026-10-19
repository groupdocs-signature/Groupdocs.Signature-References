---
title: "FileLogger"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Écrit les messages de journal dans le fichier."
type: docs
weight: 11
url: /fr/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

Écrit les messages de journal dans le fichier.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Créer un journaliseur vers le fichier. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Écrit un message d'erreur dans la console. |
|
|  | [trace(String message)](#trace-java.lang.String-) | Écrit un message de trace dans la console. |
|
|  | [warning(String message)](#warning-java.lang.String-) | Écrit un message d'avertissement dans la console; |
Les messages de journal d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Créer un journaliseur vers le fichier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileName | java.lang.String | Nom complet du fichier avec le chemin |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Écrit un message d'erreur dans la console.
Les messages de journal d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message d'erreur. |
|
|  | exception | java.lang.Exception | L'exception. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Écrit un message de trace dans la console.
Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message de trace. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Écrit un message d'avertissement dans la console;
Les messages de journal d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message d'avertissement. |
|

