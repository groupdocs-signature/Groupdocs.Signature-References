---
title: "GifSaveOptions"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Gif-formaat opslagopties voor afbeeldingsdocumenten."
type: docs
weight: 15
url: /nl/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Gif-formaat opslagopties voor afbeeldingsdocumenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | Maakt GifSaveOptions aan met standaardwaarden. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Haalt op of stelt de GIF-achtergrondkleurindex in. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Haalt op of stelt de GIF-achtergrondkleurindex in. |
|
|  | [getColorResolution()](#getColorResolution--) | Haalt op of stelt de GIF-kleuroplossing in. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | Haalt op of stelt de GIF-kleuroplossing in. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast. |
|
|  | [hasTrailer()](#hasTrailer--) | Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft. |
|
|  | [getInterlaced()](#getInterlaced--) | Waar als de afbeelding doorliggend moet zijn. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | Waar als de afbeelding doorliggend moet zijn. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd is. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd is. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | Haalt op of stelt de GIF-pixelaspectverhouding in. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Haalt op of stelt de GIF-pixelaspectverhouding in. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Maakt GifSaveOptions aan met standaardwaarden.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Haalt op of stelt de GIF-achtergrondkleurindex in.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Haalt op of stelt de GIF-achtergrondkleurindex in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Haalt op of stelt de GIF-kleuroplossing in.

<br />

*** ** * ** ***

Color Resolution - Aantal bits per primaire kleur beschikbaar voor de originele afbeelding, min 1. Deze waarde vertegenwoordigt de grootte van het volledige palet waaruit de kleuren in de grafiek zijn geselecteerd, niet het aantal kleuren dat daadwerkelijk in de grafiek wordt gebruikt. Bijvoorbeeld, als de waarde in dit veld 3 is, dan had het palet van de originele afbeelding 4 bits per primaire kleur beschikbaar om de afbeelding te maken. Deze waarde moet worden ingesteld om de rijkdom van het originele palet aan te geven, zelfs als niet elke kleur van het volledige palet beschikbaar is op de bronmachine.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Haalt op of stelt de GIF-kleuroplossing in.

<br />

*** ** * ** ***

Color Resolution - Aantal bits per primaire kleur beschikbaar voor de originele afbeelding, min 1. Deze waarde vertegenwoordigt de grootte van het volledige palet waaruit de kleuren in de grafiek zijn geselecteerd, niet het aantal kleuren dat daadwerkelijk in de grafiek wordt gebruikt. Bijvoorbeeld, als de waarde in dit veld 3 is, dan had het palet van de originele afbeelding 4 bits per primaire kleur beschikbaar om de afbeelding te maken. Deze waarde moet worden ingesteld om de rijkdom van het originele palet aan te geven, zelfs als niet elke kleur van het volledige palet beschikbaar is op de bronmachine.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast.

<br />

*** ** * ** ***

Palette correction betekent dat telkens wanneer een afbeelding naar GIF wordt geëxporteerd, de kleuren van de bronafbeelding worden geanalyseerd om het best passende palet samen te stellen (in het geval dat het afbeeldingspalet niet bestaat of niet gespecificeerd is in de opties). Het analyseproces kost wat tijd, maar de uitvoerafbeelding zal het best passende kleurenpalet hebben en het resultaat is visueel beter.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast.

<br />

*** ** * ** ***

Palette correction betekent dat telkens wanneer een afbeelding naar GIF wordt geëxporteerd, de kleuren van de bronafbeelding worden geanalyseerd om het best passende palet samen te stellen (in het geval dat het afbeeldingspalet niet bestaat of niet gespecificeerd is in de opties). Het analyseproces kost wat tijd, maar de uitvoerafbeelding zal het best passende kleurenpalet hebben en het resultaat is visueel beter.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of GIF een trailer heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Waar als de afbeelding doorliggend moet zijn.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Waar als de afbeelding doorliggend moet zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd is.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of paletinvoer gesorteerd is.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Haalt op of stelt de GIF-pixelaspectverhouding in.

<br />

*** ** * ** ***

Pixel Aspect Ratio - Factor die wordt gebruikt om een benadering van de beeldverhouding van de pixel in de originele afbeelding te berekenen. Als de waarde van het veld niet 0 is, wordt deze benadering van de beeldverhouding berekend op basis van de formule: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. De Pixel Aspect Ratio wordt gedefinieerd als het quotiënt van de breedte van de pixel gedeeld door de hoogte. Het waardebereik in dit veld maakt specificatie mogelijk van de breedste pixel van 4:1 tot de hoogste pixel van 1:4 in stappen van 1/64. Waarden: 0 - Geen informatie over beeldverhouding opgegeven. 1..255 - Waarde gebruikt bij de berekening.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Haalt op of stelt de GIF-pixelaspectverhouding in.

<br />

*** ** * ** ***

Pixel Aspect Ratio - Factor die wordt gebruikt om een benadering van de beeldverhouding van de pixel in de originele afbeelding te berekenen. Als de waarde van het veld niet 0 is, wordt deze benadering van de beeldverhouding berekend op basis van de formule: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. De Pixel Aspect Ratio wordt gedefinieerd als het quotiënt van de breedte van de pixel gedeeld door de hoogte. Het waardebereik in dit veld maakt specificatie mogelijk van de breedste pixel van 4:1 tot de hoogste pixel van 1:4 in stappen van 1/64. Waarden: 0 - Geen informatie over beeldverhouding opgegeven. 1..255 - Waarde gebruikt bij de berekening.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

