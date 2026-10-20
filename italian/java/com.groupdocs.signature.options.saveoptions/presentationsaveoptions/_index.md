---
title: "PresentationSaveOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Opzioni di salvataggio per documenti di presentazione."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Opzioni di salvataggio per documenti di presentazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Inizializza una nuova istanza della classe PresentationSaveOptions con valori predefiniti. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | Inizializza una nuova istanza della classe PresentationSaveOptions con il formato file di output specificato. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | Inizializza una nuova istanza della classe PresentationSaveOptions con il tipo di output specificato e il flag di sovrascrittura. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | Inizializza una nuova istanza della classe PresentationSaveOptions con il formato file di output specificato e il flag di sovrascrittura. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Inizializza una nuova istanza della classe PresentationSaveOptions con valori predefiniti.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


Inizializza una nuova istanza della classe PresentationSaveOptions con il formato file di output specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Tipo di file di output [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe PresentationSaveOptions con il tipo di output specificato e il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe PresentationSaveOptions con il formato file di output specificato e il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Tipo di file di output [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|
|  | overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Ottiene o imposta il formato file del documento firmato.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Ottiene o imposta il formato file del documento firmato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
