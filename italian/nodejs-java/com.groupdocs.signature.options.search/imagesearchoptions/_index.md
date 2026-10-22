---
title: "ImageSearchOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di ricerca per le firme immagine."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

Rappresenta le opzioni di ricerca per le firme immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageSearchOptions()](#ImageSearchOptions--) | Inizializza una nuova istanza della classe ImageSearchOptions con i valori predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getReturnContent()](#getReturnContent--) | Ottiene o imposta il flag per acquisire il contenuto immagine della firma nella pagina del documento. |
| [setReturnContent(boolean value)](#setReturnContent-boolean-) | Ottiene o imposta il flag per acquisire il contenuto immagine della firma nella pagina del documento. |
| [getMinContentSize()](#getMinContentSize--) | Per valore diverso da zero, questo flag specifica la dimensione minima delle immagini per i criteri di ricerca. |
| [setMinContentSize(long value)](#setMinContentSize-long-) | Per valore diverso da zero, questo flag specifica la dimensione minima delle immagini per i criteri di ricerca. |
| [getMaxContentSize()](#getMaxContentSize--) | Per valore diverso da zero, questo flag specifica la dimensione massima delle immagini per i criteri di ricerca. |
| [setMaxContentSize(long value)](#setMaxContentSize-long-) | Per valore diverso da zero, questo flag specifica la dimensione massima delle immagini per i criteri di ricerca. |
| [getReturnContentType()](#getReturnContentType--) | Specifica il tipo di file del contenuto restituito della firma immagine quando la proprietà ReturnContent è abilitata. |
| [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifica il tipo di file del contenuto restituito della firma immagine quando la proprietà ReturnContent è abilitata. |
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


Inizializza una nuova istanza della classe ImageSearchOptions con i valori predefiniti.

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Ottiene o imposta il flag per acquisire il contenuto immagine della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto della firma immagine manterrà i dati grezzi dell'immagine nel formato richiesto ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Per impostazione predefinita questa opzione è disabilitata.

**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Ottiene o imposta il flag per acquisire il contenuto immagine della firma nella pagina del documento. Se questo flag è impostato su true, il contenuto della firma immagine manterrà i dati grezzi dell'immagine nel formato richiesto ReturnContentType (\#getReturnContentType.getReturnContentType/\#setReturnContentType(FileType).setReturnContentType(FileType)). Per impostazione predefinita questa opzione è disabilitata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


Per valore diverso da zero, questo flag specifica la dimensione minima delle immagini per i criteri di ricerca. Per impostazione predefinita questo flag è impostato a zero e non influisce sul risultato della ricerca.

**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


Per valore diverso da zero, questo flag specifica la dimensione minima delle immagini per i criteri di ricerca. Per impostazione predefinita questo flag è impostato a zero e non influisce sul risultato della ricerca.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


Per valore diverso da zero, questo flag specifica la dimensione massima delle immagini per i criteri di ricerca. Per impostazione predefinita questo flag è impostato a zero e non influisce sul risultato della ricerca.

**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


Per valore diverso da zero, questo flag specifica la dimensione massima delle immagini per i criteri di ricerca. Per impostazione predefinita questo flag è impostato a zero e non influisce sul risultato della ricerca.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifica il tipo di file del contenuto restituito della firma immagine quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto dell'immagine nel formato originale. Questo formato immagine è specificato in ImageSignature.Format. I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto dell'immagine nel formato originale.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifica il tipo di file del contenuto restituito della firma immagine quando la proprietà ReturnContent è abilitata. Per impostazione predefinita è impostato a Null. Ciò significa restituire il contenuto dell'immagine nel formato originale. Questo formato immagine è specificato in ImageSignature.Format. I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP. Se il formato fornito non è supportato, verrà restituito il contenuto dell'immagine nel formato originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

