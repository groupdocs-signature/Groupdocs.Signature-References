---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Opzioni di salvataggio per l'esportazione dei documenti in immagine."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Opzioni di salvataggio per l'esportazione dei documenti in immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | Inizializza una nuova istanza della classe ExportAsImageSaveOptions con valori predefiniti. |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | Inizializza una nuova istanza della classe ExportAsImageSaveOptions con il formato file specificato. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Ottiene o imposta il numero di pagina del documento da esportare. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Ottiene o imposta il numero di pagina del documento da esportare. |
| [getExportAllPages()](#getExportAllPages--) | Flag per esportare ogni pagina. |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Flag per esportare ogni pagina. |
| [getPagesSetup()](#getPagesSetup--) | Opzioni per specificare le pagine da firmare. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opzioni per specificare le pagine da firmare. |
| [getPageColumns()](#getPageColumns--) | Ottiene o imposta il numero di colonne per le immagini esportate. |
| [setPageColumns(int value)](#setPageColumns-int-) | Ottiene o imposta il numero di colonne per le immagini esportate. |
| [getBorder()](#getBorder--) | Ottiene o imposta le impostazioni del bordo dell'immagine. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Ottiene o imposta le impostazioni del bordo dell'immagine. |
| [getTiffMultipage()](#getTiffMultipage--) | Posiziona le pagine del documento su diversi fotogrammi in un'immagine Tiff. |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Posiziona le pagine del documento su diversi fotogrammi in un'immagine Tiff. |
| [toString()](#toString--) | Sovrascrive la conversione di stringa. |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


Inizializza una nuova istanza della classe ExportAsImageSaveOptions con valori predefiniti.

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


Inizializza una nuova istanza della classe ExportAsImageSaveOptions con il formato file specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileFormat | int | Formato file dell'immagine di output. |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Ottiene o imposta il numero di pagina del documento da esportare. Il valore minimo è 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Ottiene o imposta il numero di pagina del documento da esportare. Il valore minimo è 1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Flag per esportare ogni pagina.

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Flag per esportare ogni pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opzioni per specificare le pagine da firmare.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opzioni per specificare le pagine da firmare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Ottiene o imposta il numero di colonne per le immagini esportate. Usa questa proprietà se devi posizionare le immagini in una riga.

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Ottiene o imposta il numero di colonne per le immagini esportate. Usa questa proprietà se devi posizionare le immagini in una riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Ottiene o imposta le impostazioni del bordo dell'immagine. Per impostazione predefinita questo valore non è impostato.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Ottiene o imposta le impostazioni del bordo dell'immagine. Per impostazione predefinita questo valore non è impostato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Posiziona le pagine del documento su diversi fotogrammi in un'immagine Tiff.

**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Posiziona le pagine del documento su diversi fotogrammi in un'immagine Tiff.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrive la conversione di stringa.

**Returns:**
java.lang.String -
