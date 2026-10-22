---
title: "LoadOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Consente di specificare opzioni aggiuntive come la password quando si apre un documento da firmare."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
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
| [LoadOptions()](#LoadOptions--) | Inizializza una nuova istanza della classe LoadOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPassword()](#getPassword--) | Ottiene o imposta la password per aprire un documento protetto. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password per aprire un documento protetto. |
| [getLoadExternalResources()](#getLoadExternalResources--) | Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inizializza una nuova istanza della classe LoadOptions.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene o imposta la password per aprire un documento protetto. Verrà anche utilizzata per salvare il documento firmato come protetto.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ottiene o imposta la password per aprire un documento protetto. Verrà anche utilizzata per salvare il documento firmato come protetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate. Questa opzione con valore disabilitato (false) consente di risparmiare tempo di caricamento per i documenti con molti o grandi collegamenti a risorse esterne. Per impostazione predefinita il valore è abilitato (true).

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Ottiene o imposta le opzioni che specificano se le risorse esterne del documento devono essere caricate. Questa opzione con valore disabilitato (false) consente di risparmiare tempo di caricamento per i documenti con molti o grandi collegamenti a risorse esterne. Per impostazione predefinita il valore è abilitato (true).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

