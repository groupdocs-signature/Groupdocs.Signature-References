---
title: "LoadOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Consente di specificare opzioni aggiuntive come la password quando si apre un documento da firmare."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Consente di specificare opzioni aggiuntive (come la password) quando si apre un documento da firmare.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inizializza una nuova istanza della classe LoadOptions. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ottiene o imposta la password per aprire un documento protetto. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password per aprire un documento protetto. |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate. |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate. |
|
|  | [getPermissions()](#getPermissions--) | Le autorizzazioni del documento PDF, come la stampa, la modifica e l'estrazione dei dati. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Setter interno, utilizzato dai processori di caricamento del documento per registrare le autorizzazioni analizzate dal file. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inizializza una nuova istanza della classe LoadOptions.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene o imposta la password per aprire un documento protetto.
Verrà inoltre utilizzato per salvare il documento firmato come protetto.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ottiene o imposta la password per aprire un documento protetto.
Verrà inoltre utilizzato per salvare il documento firmato come protetto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate.
Questa opzione con valore disabilitato (false) consente di risparmiare tempo di caricamento per i documenti con molti o grandi collegamenti a risorse esterne.
Il valore predefinito è abilitato (true).


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate.
Questa opzione con valore disabilitato (false) consente di risparmiare tempo di caricamento per i documenti con molti o grandi collegamenti a risorse esterne.
Il valore predefinito è abilitato (true).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


Le autorizzazioni del documento PDF, come la stampa, la modifica e l'estrazione dei dati.
Solo per documenti PDF. Solo lettura \\u2014 popolato automaticamente durante il caricamento del documento.
Il valore è una combinazione di flag proveniente da [Permissions](../../com.groupdocs.signature.options/permissions).


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Setter interno, utilizzato dai processori di caricamento del documento per registrare le autorizzazioni analizzate dal file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

