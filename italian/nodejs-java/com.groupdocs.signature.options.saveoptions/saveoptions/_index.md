---
title: "SaveOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Consente di specificare opzioni aggiuntive come la password durante il salvataggio di un documento da firmare."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Consente di specificare opzioni aggiuntive (come la password) durante il salvataggio di un documento da firmare.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | Inizializza una nuova istanza della classe SaveOptions con valori predefiniti. |
| [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | Inizializza una nuova istanza della classe SaveOptions con tipo di output e flag di sovrascrittura specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. |
| [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. |
| [getPassword()](#getPassword--) | Ottiene o imposta la password per salvare il documento firmato con protezione password. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password per salvare il documento firmato con protezione password. |
| [getUseOriginalPassword()](#getUseOriginalPassword--) | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. |
| [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. |
| [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
| [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


Inizializza una nuova istanza della classe SaveOptions con valori predefiniti.

### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


Inizializza una nuova istanza della classe SaveOptions con tipo di output e flag di sovrascrittura specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| overwriteExistingFile | boolean | Flag che indica se sovrascrivere il file firmato con lo stesso file. |

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso.

**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Ottiene o imposta se sovrascrivere il file esistente con il nuovo file di output. Altrimenti verrà creato un nuovo file con un numero come suffisso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti Image.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ottiene o imposta la password per salvare il documento firmato con protezione password. Questa proprietà non è supportata per i documenti Image.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti Image.

**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


Ottiene o imposta se utilizzare la password da LoadOptions per salvare il documento firmato come protetto. Il valore predefinito è true. Questa proprietà non è supportata per i documenti Image.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false.

**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Ottiene o imposta il flag per aggiungere automaticamente l'estensione quando mancava nel percorso del file di output. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

