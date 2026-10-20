---
title: "BarcodeSignOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le opzioni di firma Barcode."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

Rappresenta le opzioni di firma Barcode.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | Inizializza una nuova istanza della classe BarcodeSignOptions con valori predefiniti. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Inizializza una nuova istanza della classe BarcodeSignOptions con testo. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Ottiene o imposta il tipo di Barcode. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Ottiene o imposta il tipo di Barcode. |
|
|  | [getForeColor()](#getForeColor--) | Ottiene o imposta il colore di primo piano delle barre del Barcode |
L'uso di questa proprietà potrebbe causare problemi con la verifica.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Ottiene o imposta il colore di primo piano delle barre del Barcode |
L'uso di questa proprietà potrebbe causare problemi con la verifica.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Ottiene o imposta il colore di primo piano delle barre del Barcode |
L'uso di questa proprietà potrebbe causare problemi con la verifica.
|
|  | [getInnerMargins()](#getInnerMargins--) | Ottiene o imposta lo spazio tra gli elementi del Barcode e i bordi dell'immagine risultante. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Ottiene o imposta lo spazio tra gli elementi del Barcode e i bordi dell'immagine risultante. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | Ottiene o imposta l'allineamento del testo nell'immagine del Barcode risultante. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | Ottiene o imposta l'allineamento del testo nell'immagine del Barcode risultante. |
|
|  | [getReturnContent()](#getReturnContent--) | Ottiene o imposta il flag per ottenere il contenuto dell'immagine Barcode di una firma inserita nella pagina del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Ottiene o imposta il flag per ottenere il contenuto dell'immagine Barcode di una firma inserita nella pagina del documento. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Specifica il tipo di file del contenuto immagine restituito della firma Barcode quando la proprietà ReturnContent è abilitata. |
|
|  | [validate()](#validate--) | Metodo interno per convalidare i parametri delle opzioni Barcode. |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


Inizializza una nuova istanza della classe BarcodeSignOptions con valori predefiniti.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


Inizializza una nuova istanza della classe BarcodeSignOptions con testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Testo Barcode |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


Inizializza una nuova istanza della classe BarcodeSignOptions con testo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Testo Barcode |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Tipo di codifica Barcode vedi [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Ottiene o imposta il tipo di Barcode.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Ottiene o imposta il tipo di Barcode.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Ottiene o imposta il colore di primo piano delle barre del Barcode
L'uso di questa proprietà potrebbe causare problemi con la verifica. Usala con attenzione.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Ottiene o imposta il colore di primo piano delle barre del Barcode
L'uso di questa proprietà potrebbe causare problemi con la verifica. Usala con attenzione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Ottiene o imposta il colore di primo piano delle barre del Barcode
L'uso di questa proprietà potrebbe causare problemi con la verifica. Usala con attenzione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Ottiene o imposta lo spazio tra gli elementi del Barcode e i bordi dell'immagine risultante.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Ottiene o imposta lo spazio tra gli elementi del Barcode e i bordi dell'immagine risultante.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


Ottiene o imposta l'allineamento del testo nell'immagine del Barcode risultante.
Il valore predefinito è None.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


Ottiene o imposta l'allineamento del testo nell'immagine del Barcode risultante.
Il valore predefinito è None.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Ottiene o imposta il flag per ottenere il contenuto dell'immagine Barcode di una firma inserita nella pagina del documento.
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


Ottiene o imposta il flag per ottenere il contenuto dell'immagine Barcode di una firma inserita nella pagina del documento.
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
I possibili valori supportati sono: FileType.JPEG, FileType.PNG, FileType.BMP.
Se il formato fornito non è supportato, verrà restituito il contenuto immagine Barcode in formato .png.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


Metodo interno per convalidare i parametri delle opzioni Barcode.


### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
