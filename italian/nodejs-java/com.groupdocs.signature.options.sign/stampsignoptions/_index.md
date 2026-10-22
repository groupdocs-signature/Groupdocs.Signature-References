---
title: "StampSignOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Rappresenta le opzioni di firma timbro."
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Rappresenta le opzioni di firma timbro.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | Inizializza una nuova istanza della classe StampSignOptions con valori predefiniti. |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | Inizializza una nuova istanza della classe StampSignOptions con opzioni di allineamento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStampType()](#getStampType--) | Ottiene o imposta il tipo di timbro. |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Ottiene o imposta il tipo di timbro. |
| [getOuterLines()](#getOuterLines--) | Elenco delle linee esterne renderizzate come cerchi concentrici. |
| [getInnerLines()](#getInnerLines--) | Elenco delle linee interne renderizzate come insieme di rettangoli. |
| [getBackground()](#getBackground--) | Ottiene o imposta lo sfondo del timbro. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Ottiene o imposta lo sfondo del timbro. |
| [getBackgroundColor()](#getBackgroundColor--) | Ottiene o imposta il colore di sfondo della firma. |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | Ottiene o imposta il colore di sfondo della firma. |
| [getBackgroundBrush()](#getBackgroundBrush--) | Ottiene o imposta il pennello di sfondo della firma. |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | Ottiene o imposta il pennello di sfondo della firma. |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | Ottiene o imposta il tipo di ritaglio del colore di sfondo della firma. |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | Ottiene o imposta il tipo di ritaglio del colore di sfondo della firma. |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | Ottiene o imposta il tipo di ritaglio dell'immagine di sfondo della firma. |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | Ottiene o imposta il tipo di ritaglio dell'immagine di sfondo della firma. |
| [toString()](#toString--) | Sovrascrivi conversione della stringa |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


Inizializza una nuova istanza della classe StampSignOptions con valori predefiniti.

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


Inizializza una nuova istanza della classe StampSignOptions con opzioni di allineamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | La coordinata x del bordo superiore sinistro della firma timbro |
| alto | int | La coordinata y del bordo superiore sinistro della firma timbro |
| larghezza | int | La larghezza della firma timbro |
| altezza | int | L'altezza della firma timbro |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Ottiene o imposta il tipo di timbro. Il valore predefinito è Rotondo.

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Ottiene o imposta il tipo di timbro. Il valore predefinito è Rotondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Elenco delle linee esterne renderizzate come cerchi concentrici.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


Elenco delle linee interne renderizzate come insieme di rettangoli.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Ottiene o imposta lo sfondo del timbro.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Ottiene o imposta lo sfondo del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Ottiene o imposta il colore di sfondo della firma.

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


Ottiene o imposta il colore di sfondo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


Ottiene o imposta il pennello di sfondo della firma. Il valore predefinito è null.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


Ottiene o imposta il pennello di sfondo della firma. Il valore predefinito è null.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


Ottiene o imposta il tipo di ritaglio del colore di sfondo della firma.

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


Ottiene o imposta il tipo di ritaglio del colore di sfondo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


Ottiene o imposta il tipo di ritaglio dell'immagine di sfondo della firma.

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


Ottiene o imposta il tipo di ritaglio dell'immagine di sfondo della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### toString() {#toString--}
```
public String toString()
```


Sovrascrivi conversione della stringa

**Returns:**
java.lang.String -
