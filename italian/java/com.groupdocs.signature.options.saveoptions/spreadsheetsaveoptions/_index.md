---
title: "SpreadsheetSaveOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Opzioni di salvataggio per documenti di foglio di calcolo."
type: docs
weight: 14
url: /it/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Opzioni di salvataggio per documenti di foglio di calcolo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Inizializza una nuova istanza della classe SpreadsheetSaveOptions con i valori predefiniti. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | Inizializza una nuova istanza della classe SpreadsheetSaveOptions con il formato file di output predefinito. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | Inizializza una nuova istanza della classe SpreadsheetSaveOptions con il tipo di output specificato e il flag di sovrascrittura. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Inizializza una nuova istanza della classe SpreadsheetSaveOptions con i valori predefiniti.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


Inizializza una nuova istanza della classe SpreadsheetSaveOptions con il formato file di output predefinito.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Specifica il formato file di output. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe SpreadsheetSaveOptions con il tipo di output specificato e il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Specifica il formato file di output. |
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
