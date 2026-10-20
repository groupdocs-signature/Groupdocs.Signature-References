---
title: "BarcodeSearchOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le Opzioni di ricerca astratte per le firme Barcode."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Rappresenta le Opzioni di ricerca astratte per le firme Barcode.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Inizializza una nuova istanza della classe SearchBarcodeOptions con i valori predefiniti. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Inizializza una nuova istanza della classe SearchBarcodeOptions con il valore del tipo di codifica. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Inizializza una nuova istanza della classe SearchBarcodeOptions con il tipo di codifica e i valori di testo. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Specifica la proprietà Encode Type per cercare i codici a barre. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Specifica la proprietà Encode Type per cercare i codici a barre. |
|
|  | [getText()](#getText--) | Specifica il testo della firma Barcode se deve essere cercato e confrontato. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Specifica il testo della firma Barcode se deve essere cercato e confrontato. |
|
|  | [getMatchType()](#getMatchType--) | Ottiene o imposta la ricerca del tipo di corrispondenza del testo Barcode. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Ottiene o imposta la ricerca del tipo di corrispondenza del testo Barcode. |
|
|  | [getReturnContent()](#getReturnContent--) | Ottiene o imposta il flag per acquisire il contenuto dell'immagine Barcode della firma nella pagina del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Ottiene o imposta il flag per acquisire il contenuto dell'immagine Barcode della firma nella pagina del documento. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Inizializza una nuova istanza della classe SearchBarcodeOptions con i valori predefiniti.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Inizializza una nuova istanza della classe SearchBarcodeOptions con il valore del tipo di codifica.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Specifica il tipo di codifica Barcode. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Inizializza una nuova istanza della classe SearchBarcodeOptions con il tipo di codifica e i valori di testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Specifica il tipo di codifica Barcode. |
|
|  | testo | java.lang.String | Imposta il testo della firma Barcode. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Specifica la proprietà Encode Type per cercare i codici a barre.
Se questo valore non è impostato, la ricerca viene eseguita per tutti i tipi di Barcode supportati


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Specifica la proprietà Encode Type per cercare i codici a barre.
Se questo valore non è impostato, la ricerca viene eseguita per tutti i tipi di Barcode supportati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Specifica il testo della firma Barcode se deve essere cercato e confrontato.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specifica il testo della firma Barcode se deve essere cercato e confrontato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Ottiene o imposta la ricerca del tipo di corrispondenza del testo Barcode. Viene utilizzato solo quando la proprietà Text è impostata.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Ottiene o imposta la ricerca del tipo di corrispondenza del testo Barcode. Viene utilizzato solo quando la proprietà Text è impostata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Ottiene o imposta il flag per acquisire il contenuto dell'immagine Barcode della firma nella pagina del documento.
Se questo flag è impostato su true, il contenuto immagine della firma Barcode manterrà i dati grezzi dell'immagine nel formato richiesto.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Per impostazione predefinita questa opzione è disabilitata.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Ottiene o imposta il flag per acquisire il contenuto dell'immagine Barcode della firma nella pagina del documento.
Se questo flag è impostato su true, il contenuto immagine della firma Barcode manterrà i dati grezzi dell'immagine nel formato richiesto.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Per impostazione predefinita questa opzione è disabilitata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata.
Per impostazione predefinita è impostato su Null. Ciò significa restituire il contenuto immagine Barcode nel formato originale.
Questo formato immagine è specificato in
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP.
Se il formato fornito non è supportato, verrà restituito il contenuto immagine Barcode in formato .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata.
Per impostazione predefinita è impostato su Null. Ciò significa restituire il contenuto immagine Barcode nel formato originale.
Questo formato immagine è specificato in
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP.
Se il formato fornito non è supportato, verrà restituito il contenuto immagine Barcode in formato .png.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

