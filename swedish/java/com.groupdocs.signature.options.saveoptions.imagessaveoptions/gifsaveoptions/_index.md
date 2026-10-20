---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Gif-formatets sparalternativ för bilddokument."
type: docs
weight: 15
url: /sv/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Gif-formatets sparalternativ för bilddokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | Skapar GifSaveOptions med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Hämtar eller anger GIF:s bakgrundsfärgsindex. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Hämtar eller anger GIF:s bakgrundsfärgsindex. |
|
|  | [getColorResolution()](#getColorResolution--) | Hämtar eller anger GIF:s färguppslagning. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | Hämtar eller anger GIF:s färguppslagning. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Hämtar eller anger ett värde som indikerar om palettekorrigering tillämpas. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Hämtar eller anger ett värde som indikerar om palettekorrigering tillämpas. |
|
|  | [hasTrailer()](#hasTrailer--) | Hämtar eller anger ett värde som indikerar om GIF har trailer. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | Hämtar eller anger ett värde som indikerar om GIF har trailer. |
|
|  | [getInterlaced()](#getInterlaced--) | Sant om bilden ska vara interlaced. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | Sant om bilden ska vara interlaced. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | Hämtar eller anger ett värde som indikerar om paletteposter är sorterade. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Hämtar eller anger ett värde som indikerar om paletteposter är sorterade. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | Hämtar eller anger GIF:s pixelaspektförhållande. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Hämtar eller anger GIF:s pixelaspektförhållande. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Skapar GifSaveOptions med standardvärden.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Hämtar eller anger GIF:s bakgrundsfärgsindex.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Hämtar eller anger GIF:s bakgrundsfärgsindex.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Hämtar eller anger GIF:s färguppslagning.

<br />

*** ** * ** ***

Color Resolution - Antal bitar per primärfärg som är tillgängliga i originalbilden, minus 1. Detta värde representerar storleken på hela paletten som färgerna i grafiken valdes från, inte antalet färger som faktiskt används i grafiken. Till exempel, om värdet i detta fält är 3, hade paletten i originalbilden 4 bitar per primärfärg tillgängliga för att skapa bilden. Detta värde bör sättas för att ange rikedomen i originalpaletten, även om inte varje färg från hela paletten är tillgänglig på källmaskinen.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Hämtar eller anger GIF:s färguppslagning.

<br />

*** ** * ** ***

Color Resolution - Antal bitar per primärfärg som är tillgängliga i originalbilden, minus 1. Detta värde representerar storleken på hela paletten som färgerna i grafiken valdes från, inte antalet färger som faktiskt används i grafiken. Till exempel, om värdet i detta fält är 3, hade paletten i originalbilden 4 bitar per primärfärg tillgängliga för att skapa bilden. Detta värde bör sättas för att ange rikedomen i originalpaletten, även om inte varje färg från hela paletten är tillgänglig på källmaskinen.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Hämtar eller anger ett värde som indikerar om palettekorrigering tillämpas.

<br />

*** ** * ** ***

Palettekorrigering innebär att när en bild exporteras till GIF analyseras källbildens färger för att bygga den bäst matchande paletten (om bildens Palette inte finns eller inte specificerats i alternativen). Analysprocessen tar viss tid, men den resulterande bilden får den bäst matchande färgpaletten och resultatet blir visuellt bättre.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Hämtar eller anger ett värde som indikerar om palettekorrigering tillämpas.

<br />

*** ** * ** ***

Palettekorrigering innebär att när en bild exporteras till GIF analyseras källbildens färger för att bygga den bäst matchande paletten (om bildens Palette inte finns eller inte specificerats i alternativen). Analysprocessen tar viss tid, men den resulterande bilden får den bäst matchande färgpaletten och resultatet blir visuellt bättre.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Hämtar eller anger ett värde som indikerar om GIF har trailer.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Hämtar eller anger ett värde som indikerar om GIF har trailer.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Sant om bilden ska vara interlaced.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Sant om bilden ska vara interlaced.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Hämtar eller anger ett värde som indikerar om paletteposter är sorterade.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Hämtar eller anger ett värde som indikerar om paletteposter är sorterade.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Hämtar eller anger GIF:s pixelaspektförhållande.

<br />

*** ** * ** ***

Pixel Aspect Ratio - Faktor som används för att beräkna en approximation av pixelns bildförhållande i originalbilden. Om fältets värde inte är 0 beräknas denna approximation av bildförhållandet enligt formeln: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio definieras som kvoten mellan pixelns bredd och dess höjd. Värdeintervallet i detta fält möjliggör specificering av den bredaste pixeln 4:1 till den högsta pixeln 1:4 i steg om 1/64. Värden: 0 – Ingen information om bildförhållande ges. 1..255 – Värde som används i beräkningen.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Hämtar eller anger GIF:s pixelaspektförhållande.

<br />

*** ** * ** ***

Pixel Aspect Ratio - Faktor som används för att beräkna en approximation av pixelns bildförhållande i originalbilden. Om fältets värde inte är 0 beräknas denna approximation av bildförhållandet enligt formeln: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio definieras som kvoten mellan pixelns bredd och dess höjd. Värdeintervallet i detta fält möjliggör specificering av den bredaste pixeln 4:1 till den högsta pixeln 1:4 i steg om 1/64. Värden: 0 – Ingen information om bildförhållande ges. 1..255 – Värde som används i beräkningen.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte |  |

