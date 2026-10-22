---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di ricerca astratte per le firme di metadati."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Rappresenta le opzioni di ricerca astratte per le firme di metadati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MetadataSearchOptions()](#MetadataSearchOptions--) | Inizializza una nuova istanza della classe SearchMetadataOptions con i valori predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Specifica il nome della firma Metadata se deve essere cercato e corrisposto. |
| [setName(String value)](#setName-java.lang.String-) | Specifica il nome della firma Metadata se deve essere cercato e corrisposto. |
| [getNameMatchType()](#getNameMatchType--) | Ottiene o imposta il tipo di corrispondenza del nome Metadata nella ricerca. |
| [setNameMatchType(int value)](#setNameMatchType-int-) | Ottiene o imposta il tipo di corrispondenza del nome Metadata nella ricerca. |
| [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | Indica se le proprietà integrate del documento, come statistiche del documento, informazioni, ecc., devono essere incluse nel risultato della ricerca. |
| [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | Indica se le proprietà integrate del documento, come statistiche del documento, informazioni, ecc., devono essere incluse nel risultato della ricerca. |
| [getDataEncryption()](#getDataEncryption--) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code. |
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


Inizializza una nuova istanza della classe SearchMetadataOptions con i valori predefiniti.

### getName() {#getName--}
```
public final String getName()
```


Specifica il nome della firma Metadata se deve essere cercato e corrisposto.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Specifica il nome della firma Metadata se deve essere cercato e corrisposto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


Ottiene o imposta il tipo di corrispondenza del nome Metadata nella ricerca. Viene utilizzato solo quando la proprietà Name è impostata.

**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


Ottiene o imposta il tipo di corrispondenza del nome Metadata nella ricerca. Viene utilizzato solo quando la proprietà Name è impostata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


Indica se le proprietà integrate del documento, come statistiche del documento, informazioni, ecc., devono essere incluse nel risultato della ricerca. Questa opzione è rilevante per i tipi di file di presentazione, foglio di calcolo e elaborazione testi.

**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


Indica se le proprietà integrate del documento, come statistiche del documento, informazioni, ecc., devono essere incluse nel risultato della ricerca. Questa opzione è rilevante per i tipi di file di presentazione, foglio di calcolo e elaborazione testi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Ottiene o imposta l'implementazione dell'interfaccia [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) per codificare e decodificare le proprietà Testo o Dati della firma QR-Code.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

