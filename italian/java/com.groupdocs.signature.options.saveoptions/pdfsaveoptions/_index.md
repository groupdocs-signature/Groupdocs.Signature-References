---
title: "PdfSaveOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Opzioni di salvataggio per documenti PDF."
type: docs
weight: 11
url: /it/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
|  | [PdfSaveOptions()](#PdfSaveOptions--) | Inizializza una nuova istanza della classe PdfSaveOptions con valori predefiniti. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | Inizializza una nuova istanza della classe PdfSaveOptions con il formato file di output specificato. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | Inizializza una nuova istanza della classe PdfSaveOptions con il flag di sovrascrittura. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | Inizializza una nuova istanza della classe PdfSaveOptions con il formato file di output specificato e il flag di sovrascrittura. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Ottiene o imposta il formato file del documento firmato. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Una password di autorizzazione (la password primaria) richiede una password per modificare le impostazioni di autorizzazione. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Una password di autorizzazione (la password primaria) richiede una password per modificare le impostazioni di autorizzazione. |
|
|  | [getPermissions()](#getPermissions--) | Le autorizzazioni del documento PDF, come la stampa, la modifica e l'estrazione dei dati. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Le autorizzazioni del documento PDF, come la stampa, la modifica e l'estrazione dei dati. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


Inizializza una nuova istanza della classe PdfSaveOptions con valori predefiniti.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


Inizializza una nuova istanza della classe PdfSaveOptions con il formato file di output specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Tipo di file di output [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe PdfSaveOptions con il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe PdfSaveOptions con il formato file di output specificato e il flag di sovrascrittura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileFormat | int | Tipo di file di output [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Una password di autorizzazione (la password primaria) richiede una password per modificare le impostazioni di autorizzazione.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Una password di autorizzazione (la password primaria) richiede una password per modificare le impostazioni di autorizzazione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Le autorizzazioni del documento PDF, come la stampa, la modifica e l'estrazione dei dati.


Per modificare queste autorizzazioni, la
PermissionsPassword
deve essere impostata.
Il valore è una combinazione di flag proveniente da [Permissions](../../com.groupdocs.signature.options/permissions).
Un
null
valore indica che non sono applicate autorizzazioni esplicite.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Le autorizzazioni del documento PDF, come la stampa, la modifica e l'estrazione dei dati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
