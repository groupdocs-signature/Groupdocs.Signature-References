---
title: "ImageSignOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta le opzioni di firma immagine."
type: docs
weight: 13
url: /it/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Rappresenta le opzioni di firma immagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | Inizializza una nuova istanza della classe ImageSignOptions con valori predefiniti. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | Inizializza una nuova istanza della classe ImageSignOptions con un file immagine. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | Inizializza una nuova istanza della classe ImageSignOptions con un flusso di immagine. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Ottiene o imposta il percorso del file immagine della firma. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Ottiene o imposta il percorso del file immagine della firma. |
|
|  | [getImageStream()](#getImageStream--) | Ottiene o imposta il flusso immagine della firma. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Ottiene o imposta il flusso immagine della firma. |
|
|  | [getLeft()](#getLeft--) | Posizione X sinistra della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setLeft(int value)](#setLeft-int-) | Posizione X sinistra della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getTop()](#getTop--) | Posizione Y superiore della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [setTop(int value)](#setTop-int-) | Posizione Y superiore della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
|
|  | [getWidth()](#getWidth--) | Larghezza della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Larghezza della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Altezza della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setHeight(int value)](#setHeight-int-) | Altezza della Firma sulla pagina del documento in valori di misura. |
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Sinistra e Superiore. |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Sinistra e Superiore. |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza. |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza. |
|
|  | [getStretch()](#getStretch--) | Modalità di allungamento sulla pagina del documento. |
|
|  | [setStretch(int value)](#setStretch-int-) | Modalità di allungamento sulla pagina del documento. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Angolo di rotazione della firma sulla pagina del documento (orario). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Angolo di rotazione della firma sulla pagina del documento (orario). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Allineamento orizzontale della firma sulla pagina del documento. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Allineamento orizzontale della firma sulla pagina del documento. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Allineamento verticale della firma sulla pagina del documento. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Allineamento verticale della firma sulla pagina del documento. |
|
|  | [getMargin()](#getMargin--) | Ottiene o imposta lo spazio tra i bordi della Firma e del Documento. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | Ottiene o imposta lo spazio tra i bordi della Firma e del Documento. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine. |
|
|  | [getTransparency()](#getTransparency--) | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). |
|
|  | [getShapePosition()](#getShapePosition--) | Definisce dove la forma dovrebbe essere presentata nel layout del documento |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Definisce dove la forma dovrebbe essere presentata nel layout del documento |
|
|  | [getRectangle()](#getRectangle--) | Rettangolo dell'area in cui inserire l'immagine nel documento. |
|
|  | [getBorder()](#getBorder--) | Specifica le impostazioni del bordo |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Specifica le impostazioni del bordo |
|
|  | [toString()](#toString--) | Sovrascrivi la conversione di stringa. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Crea una nuova istanza della classe ImageSignOptions con immagine predefinita da Base64. |
|
|  | [dispose()](#dispose--) | Cancella le risorse interne |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


Inizializza una nuova istanza della classe ImageSignOptions con valori predefiniti.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


Inizializza una nuova istanza della classe ImageSignOptions con un file immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Percorso del file immagine |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


Inizializza una nuova istanza della classe ImageSignOptions con un flusso di immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Stream dell'immagine |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Ottiene o imposta il percorso del file immagine della firma.
Questa proprietà è utilizzata solo se ImageStream non è specificato.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Ottiene o imposta il percorso del file immagine della firma.
Questa proprietà è utilizzata solo se ImageStream non è specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Ottiene o imposta il flusso immagine della firma.
Se questa proprietà è specificata, viene sempre utilizzata al posto di ImageGuid.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Ottiene o imposta il flusso immagine della firma.
Se questa proprietà è specificata, viene sempre utilizzata al posto di ImageGuid.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Posizione X sinistra della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funziona se l'allineamento orizzontale non è specificato).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Posizione X sinistra della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funziona se l'allineamento orizzontale non è specificato).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Posizione Y superiore della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funziona se l'allineamento verticale non è specificato).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Posizione Y superiore della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType).
(funziona se l'allineamento verticale non è specificato).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Larghezza della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Larghezza della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altezza della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altezza della Firma sulla pagina del documento in valori di misura.
(pixel, percentuali o millimetri vedi [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Sinistra e Superiore.


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Sinistra e Superiore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza.


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Tipo di misura (pixel, percentuali o millimetri) per le proprietà Larghezza e Altezza.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Modalità di allungamento sulla pagina del documento.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Modalità di allungamento sulla pagina del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Angolo di rotazione della firma sulla pagina del documento (orario).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Angolo di rotazione della firma sulla pagina del documento (orario).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Allineamento orizzontale della firma sulla pagina del documento.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Allineamento orizzontale della firma sulla pagina del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Allineamento verticale della firma sulla pagina del documento.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Allineamento verticale della firma sulla pagina del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


Ottiene o imposta lo spazio tra i bordi della Firma e del Documento.
(funziona SOLO se l'allineamento orizzontale o verticale è specificato).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


Ottiene o imposta lo spazio tra i bordi della Firma e del Documento.
(funziona SOLO se l'allineamento orizzontale o verticale è specificato).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Ottiene o imposta il tipo di misura (pixel, percentuali o millimetri) per il margine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Ottiene o imposta la trasparenza della firma (valore da 0,0 (opaco) a 1,0 (trasparente)). Il valore predefinito è 0 (opaco).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Definisce dove la forma dovrebbe essere presentata nel layout del documento


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Definisce dove la forma dovrebbe essere presentata nel layout del documento


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Rettangolo dell'area in cui inserire l'immagine nel documento.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Specifica le impostazioni del bordo


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Specifica le impostazioni del bordo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi la conversione di stringa.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Crea una nuova istanza della classe ImageSignOptions con immagine predefinita da Base64.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | base64Content | java.lang.String | Contenuto dell'immagine in formato stringa Base64 |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Cancella le risorse interne


