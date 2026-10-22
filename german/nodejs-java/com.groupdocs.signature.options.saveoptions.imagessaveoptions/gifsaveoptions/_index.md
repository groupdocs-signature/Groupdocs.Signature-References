---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Gif-Format-Speicheroptionen für Bilddokumente."
type: docs
weight: 15
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Gif-Format-Speicheroptionen für Bilddokumente.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | Erstellt GifSaveOptions mit Standardwerten. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Liest oder setzt den GIF-Hintergrundfarbindex. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Liest oder setzt den GIF-Hintergrundfarbindex. |
| [getColorResolution()](#getColorResolution--) | Liest oder setzt die GIF-Farbauflösung. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Liest oder setzt die GIF-Farbauflösung. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird. |
| [hasTrailer()](#hasTrailer--) | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
| [getInterlaced()](#getInterlaced--) | True, wenn das Bild interlaced sein soll. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True, wenn das Bild interlaced sein soll. |
| [isPaletteSorted()](#isPaletteSorted--) | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Liest oder setzt das GIF-Pixel-Seitenverhältnis. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Liest oder setzt das GIF-Pixel-Seitenverhältnis. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Erstellt GifSaveOptions mit Standardwerten.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Liest oder setzt den GIF-Hintergrundfarbindex.

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Liest oder setzt den GIF-Hintergrundfarbindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Liest oder setzt die GIF-Farbauflösung.

--------------------

Farbauflösung - Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben im Bild ausgewählt wurden, nicht die Anzahl der tatsächlich im Bild verwendeten Farben. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, dann hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Verfügung, um das Bild zu erstellen. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe aus der gesamten Palette auf der Quellmaschine verfügbar ist.

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Liest oder setzt die GIF-Farbauflösung.

--------------------

Farbauflösung - Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben im Bild ausgewählt wurden, nicht die Anzahl der tatsächlich im Bild verwendeten Farben. Zum Beispiel, wenn der Wert in diesem Feld 3 ist, dann hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Verfügung, um das Bild zu erstellen. Dieser Wert sollte gesetzt werden, um die Reichhaltigkeit der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe aus der gesamten Palette auf der Quellmaschine verfügbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird.

--------------------

Die Palettenkorrektur bedeutet, dass jedes Mal, wenn ein Bild als GIF exportiert wird, die Farben des Quellbildes analysiert werden, um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang dauert etwas, jedoch wird das Ausgabebild die bestpassende Farbpalette besitzen und das Ergebnis ist visuell besser.

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob eine Palettenkorrektur angewendet wird.

--------------------

Die Palettenkorrektur bedeutet, dass jedes Mal, wenn ein Bild als GIF exportiert wird, die Farben des Quellbildes analysiert werden, um die bestmögliche passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang dauert etwas, jedoch wird das Ausgabebild die bestpassende Farbpalette besitzen und das Ergebnis ist visuell besser.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat.

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True, wenn das Bild interlaced sein soll.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True, wenn das Bild interlaced sein soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind.

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Liest oder setzt das GIF-Pixel-Seitenverhältnis.

--------------------

Pixel Aspect Ratio – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert des Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Das Pixel Aspect Ratio ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Es werden keine Informationen zum Seitenverhältnis angegeben. 1..255 – Wert, der in der Berechnung verwendet wird.

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Liest oder setzt das GIF-Pixel-Seitenverhältnis.

--------------------

Pixel Aspect Ratio – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert des Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Das Pixel Aspect Ratio ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Es werden keine Informationen zum Seitenverhältnis angegeben. 1..255 – Wert, der in der Berechnung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

