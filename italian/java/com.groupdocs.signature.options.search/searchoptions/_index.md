---
title: "SearchOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le opzioni di estrazione delle firme dal documento."
type: docs
weight: 17
url: /it/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Rappresenta le opzioni di estrazione delle firme dal documento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Ottiene o imposta il numero di pagina del documento per la ricerca. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Ottiene o imposta il numero di pagina del documento per la ricerca. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Opzioni per specificare le pagine per la ricerca della firma. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Opzioni per specificare le pagine per la ricerca della firma. |
|
|  | [getAllPages()](#getAllPages--) | Flag per cercare su ogni pagina del documento. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Flag per cercare su ogni pagina del documento. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Flag per restituire solo le firme contrassegnate come IsSignature. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Flag per restituire solo le firme contrassegnate come IsSignature. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Metodo virtuale per ottenere l'elenco delle pagine per l'estrazione della firma. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Ottiene o imposta il numero di pagina del documento per la ricerca.
Il valore è opzionale.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Ottiene o imposta il numero di pagina del documento per la ricerca.
Il valore è opzionale.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Opzioni per specificare le pagine per la ricerca della firma.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Opzioni per specificare le pagine per la ricerca della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Flag per cercare su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Flag per cercare su ogni pagina del documento. Per impostazione predefinita questo valore è impostato su true.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Flag per restituire solo le firme contrassegnate come IsSignature. Per impostazione predefinita il valore è false, il che indica di restituire tutte le firme che corrispondono ai criteri specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Metodo virtuale per ottenere l'elenco delle pagine per l'estrazione della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | totalPages | int | Conteggio totale delle pagine |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Elenco dei numeri di pagina

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
