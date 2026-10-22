---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Opzioni di salvataggio per documenti PDF."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

Opzioni di salvataggio per documenti PDF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | Inizializza una nuova istanza della classe PdfSaveOptions con valori predefiniti. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Inizializza una nuova istanza della classe PdfSaveOptions con il formato di file di output specificato. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Inizializza una nuova istanza della classe PdfSaveOptions con il flag di sovrascrittura. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Inizializza una nuova istanza della classe PdfSaveOptions con il formato di file di output specificato e il flag di sovrascrittura. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Ottiene o imposta il formato del file del documento firmato. |
| [setFileFormat(int value)](#setFileFormat-int-) | Ottiene o imposta il formato del file del documento firmato. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Inizializza una nuova istanza della classe PdfSaveOptions con valori predefiniti.

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Inizializza una nuova istanza della classe PdfSaveOptions con il formato di file di output specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileFormat | int | Tipo di file di output [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe PdfSaveOptions con il flag di sovrascrittura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe PdfSaveOptions con il formato di file di output specificato e il flag di sovrascrittura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileFormat | int | Tipo di file di output [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
| overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Ottiene o imposta il formato del file del documento firmato.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Ottiene o imposta il formato del file del documento firmato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
