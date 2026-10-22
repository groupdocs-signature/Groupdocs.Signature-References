---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Opzioni di salvataggio del formato Gif per documenti immagine."
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Opzioni di salvataggio del formato Gif per documenti immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | Crea GifSaveOptions con valori predefiniti. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [getColorResolution()](#getColorResolution--) | Ottiene o imposta la risoluzione colore GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Ottiene o imposta la risoluzione colore GIF. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata. |
| [hasTrailer()](#hasTrailer--) | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Ottiene o imposta un valore che indica se il GIF ha un trailer. |
| [getInterlaced()](#getInterlaced--) | True se l'immagine deve essere interlacciata. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True se l'immagine deve essere interlacciata. |
| [isPaletteSorted()](#isPaletteSorted--) | Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Ottiene o imposta il rapporto d'aspetto dei pixel GIF. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Crea GifSaveOptions con valori predefiniti.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Ottiene o imposta l'indice del colore di sfondo GIF.

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Ottiene o imposta l'indice del colore di sfondo GIF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Ottiene o imposta la risoluzione colore GIF.

--------------------

Color Resolution - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori del grafico, non il numero di colori effettivamente utilizzati nel grafico. Per esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine.

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Ottiene o imposta la risoluzione colore GIF.

--------------------

Color Resolution - Numero di bit per colore primario disponibili nell'immagine originale, meno 1. Questo valore rappresenta la dimensione dell'intera tavolozza da cui sono stati selezionati i colori del grafico, non il numero di colori effettivamente utilizzati nel grafico. Per esempio, se il valore in questo campo è 3, allora la tavolozza dell'immagine originale aveva 4 bit per colore primario disponibili per creare l'immagine. Questo valore dovrebbe essere impostato per indicare la ricchezza della tavolozza originale, anche se non tutti i colori dell'intera tavolozza sono disponibili sulla macchina di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata.

--------------------

La correzione della Palette significa che ogni volta che l'immagine viene esportata in GIF i colori dell'immagine sorgente verranno analizzati per costruire la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine di output avrà la palette di colori più corrispondente e il risultato sarà visivamente migliore.

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Ottiene o imposta un valore che indica se la correzione della tavolozza è applicata.

--------------------

La correzione della Palette significa che ogni volta che l'immagine viene esportata in GIF i colori dell'immagine sorgente verranno analizzati per costruire la palette più adatta (nel caso in cui la Palette dell'immagine non esista o non sia specificata nelle opzioni). Il processo di analisi richiede del tempo, tuttavia l'immagine di output avrà la palette di colori più corrispondente e il risultato sarà visivamente migliore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Ottiene o imposta un valore che indica se il GIF ha un trailer.

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Ottiene o imposta un valore che indica se il GIF ha un trailer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True se l'immagine deve essere interlacciata.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True se l'immagine deve essere interlacciata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate.

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

--------------------

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto viene calcolata in base alla formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Ottiene o imposta il rapporto d'aspetto dei pixel GIF.

--------------------

Pixel Aspect Ratio - Fattore usato per calcolare un'approssimazione del rapporto d'aspetto del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione del rapporto d'aspetto viene calcolata in base alla formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Il Pixel Aspect Ratio è definito come il quoziente tra la larghezza del pixel e la sua altezza. L'intervallo di valori in questo campo consente di specificare il pixel più largo da 4:1 al pixel più alto da 1:4 in incrementi di 1/64. Valori: 0 - Nessuna informazione sul rapporto d'aspetto fornita. 1..255 - Valore usato nel calcolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

