---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Gif-Format-Speicheroptionen für Bilddokumente."
type: docs
weight: 15
url: /de/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
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
|  | [GifSaveOptions()](#GifSaveOptions--) | Erstellt GifSaveOptions mit Standardwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Liest oder setzt den GIF-Hintergrundfarbindizes. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Liest oder setzt den GIF-Hintergrundfarbindizes. |
|
|  | [getColorResolution()](#getColorResolution--) | Liest oder setzt die GIF-Farbauflösung. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | Liest oder setzt die GIF-Farbauflösung. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Liest oder setzt einen Wert, der angibt, ob die Palettenkorrektur angewendet wird. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Palettenkorrektur angewendet wird. |
|
|  | [hasTrailer()](#hasTrailer--) | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | Liest oder setzt einen Wert, der angibt, ob das GIF einen Trailer hat. |
|
|  | [getInterlaced()](#getInterlaced--) | Wahr, wenn das Bild interlaced sein soll. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | Wahr, wenn das Bild interlaced sein soll. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Liest oder setzt einen Wert, der angibt, ob Paletteneinträge sortiert sind. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | Liest oder setzt das GIF-Pixel-Seitenverhältnis. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Liest oder setzt das GIF-Pixel-Seitenverhältnis. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Erstellt GifSaveOptions mit Standardwerten.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Liest oder setzt den GIF-Hintergrundfarbindizes.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Liest oder setzt den GIF-Hintergrundfarbindizes.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Liest oder setzt die GIF-Farbauflösung.

<br />

*** ** * ** ***

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben der Grafik ausgewählt wurden, nicht die tatsächlich in der Grafik verwendete Farbanzahl. Beispiel: Wenn der Wert in diesem Feld 3 ist, hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Erstellung des Bildes. Dieser Wert sollte gesetzt werden, um den Reichtum der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Liest oder setzt die GIF-Farbauflösung.

<br />

*** ** * ** ***

Farbauflösung – Anzahl der Bits pro Primärfarbe, die dem Originalbild zur Verfügung stehen, minus 1. Dieser Wert stellt die Größe der gesamten Palette dar, aus der die Farben der Grafik ausgewählt wurden, nicht die tatsächlich in der Grafik verwendete Farbanzahl. Beispiel: Wenn der Wert in diesem Feld 3 ist, hatte die Palette des Originalbildes 4 Bits pro Primärfarbe zur Erstellung des Bildes. Dieser Wert sollte gesetzt werden, um den Reichtum der Originalpalette anzuzeigen, selbst wenn nicht jede Farbe der gesamten Palette auf der Quellmaschine verfügbar ist.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Liest oder setzt einen Wert, der angibt, ob die Palettenkorrektur angewendet wird.

<br />

*** ** * ** ***

Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden, um die am besten passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang benötigt zwar etwas Zeit, jedoch erhält das Ausgabebild die optimal passende Farbpalette, wodurch das Ergebnis visuell besser ist.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Palettenkorrektur angewendet wird.

<br />

*** ** * ** ***

Palettenkorrektur bedeutet, dass bei jedem Export eines Bildes zu GIF die Farben des Quellbildes analysiert werden, um die am besten passende Palette zu erstellen (falls die Bildpalette nicht existiert oder in den Optionen nicht angegeben ist). Der Analysevorgang benötigt zwar etwas Zeit, jedoch erhält das Ausgabebild die optimal passende Farbpalette, wodurch das Ergebnis visuell besser ist.

<br />



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


Wahr, wenn das Bild interlaced sein soll.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Wahr, wenn das Bild interlaced sein soll.


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

<br />

*** ** * ** ***

Pixel-Seitenverhältnis – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert dieses Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Seitenverhältnis = (Pixel-Seitenverhältnis + 15) / 64. Das Pixel-Seitenverhältnis ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Keine Informationen zum Seitenverhältnis angegeben. 1..255 – Für die Berechnung verwendeter Wert.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Liest oder setzt das GIF-Pixel-Seitenverhältnis.

<br />

*** ** * ** ***

Pixel-Seitenverhältnis – Faktor, der verwendet wird, um eine Annäherung des Seitenverhältnisses des Pixels im Originalbild zu berechnen. Wenn der Wert dieses Feldes nicht 0 ist, wird diese Annäherung des Seitenverhältnisses anhand der Formel berechnet: Seitenverhältnis = (Pixel-Seitenverhältnis + 15) / 64. Das Pixel-Seitenverhältnis ist definiert als das Verhältnis der Pixelbreite zur Pixelhöhe. Der Wertebereich in diesem Feld ermöglicht die Angabe des breitesten Pixels von 4:1 bis zum höchsten Pixel von 1:4 in Schritten von 1/64. Werte: 0 – Keine Informationen zum Seitenverhältnis angegeben. 1..255 – Für die Berechnung verwendeter Wert.

<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

