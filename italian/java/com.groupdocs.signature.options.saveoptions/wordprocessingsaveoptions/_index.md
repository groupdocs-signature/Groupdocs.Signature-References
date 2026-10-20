---
title: "WordProcessingSaveOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Opzioni di salvataggio per documenti di elaborazione testi."
type: docs
weight: 15
url: /it/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Opzioni di salvataggio per documenti di elaborazione testi.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con i valori predefiniti. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con il formato file di output specificato. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con il tipo di output specificato e il flag di sovrascrittura. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | Inizializza una nuova istanza della classe WordProcessingSaveOptions con il formato file di output specificato e il flag di sovrascrittura. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Inizializza una nuova istanza della classe WordProcessingSaveOptions con i valori predefiniti.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


Inizializza una nuova istanza della classe WordProcessingSaveOptions con il formato file di output specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Tipo di file di output [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe WordProcessingSaveOptions con il tipo di output specificato e il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe WordProcessingSaveOptions con il formato file di output specificato e il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Tipo di file di output [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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


Sovrascrivi la conversione di stringa


**Returns:**
java.lang.String -
