---
title: "PreviewOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di anteprima del documento."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Rappresenta le opzioni di anteprima del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | Inizializza l'oggetto PreviewOptions. |
| [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | Inizializza l'oggetto PreviewOptions. |
| [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | Inizializza l'oggetto PreviewOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza delle immagini di anteprima. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta la larghezza delle immagini di anteprima. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza delle immagini di anteprima. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta l'altezza delle immagini di anteprima. |
| [getPageNumbers()](#getPageNumbers--) | Ottiene o imposta i numeri di pagina delle immagini di anteprima. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ottiene o imposta i numeri di pagina delle immagini di anteprima. |
| [getPreviewFormat()](#getPreviewFormat--) | Ottiene o imposta il formato delle immagini di anteprima. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | Ottiene o imposta il formato delle immagini di anteprima. |
| [getHideSignatures()](#getHideSignatures--) | Ottiene o imposta il flag per nascondere le firme dall'immagine di anteprima della pagina. |
| [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | Ottiene o imposta il flag per nascondere le firme dall'immagine di anteprima della pagina. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


Inizializza l'oggetto PreviewOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | Interfaccia che definisce il metodo per creare lo stream di anteprima della pagina di output. |
| pageNumbers | int[] | Numeri di pagina desiderati |

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


Inizializza l'oggetto PreviewOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | Interfaccia che definisce il metodo per creare lo stream di anteprima della pagina di output. |
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


Inizializza l'oggetto PreviewOptions.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Percorso del file di output. |
| pageNumbers | int[] | Numeri di pagina desiderati |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene o imposta la larghezza delle immagini di anteprima.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ottiene o imposta la larghezza delle immagini di anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene o imposta l'altezza delle immagini di anteprima.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ottiene o imposta l'altezza delle immagini di anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ottiene o imposta i numeri di pagina delle immagini di anteprima.

**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ottiene o imposta i numeri di pagina delle immagini di anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Ottiene o imposta il formato delle immagini di anteprima.

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Ottiene o imposta il formato delle immagini di anteprima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


Ottiene o imposta il flag per nascondere le firme dall'immagine di anteprima della pagina. Solo le firme contrassegnate come IsSignature saranno nascoste dall'immagine della pagina del documento generato.

**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


Ottiene o imposta il flag per nascondere le firme dall'immagine di anteprima della pagina. Solo le firme contrassegnate come IsSignature saranno nascoste dall'immagine della pagina del documento generato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

