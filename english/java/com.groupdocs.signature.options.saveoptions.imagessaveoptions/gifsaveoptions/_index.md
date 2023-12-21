---
title: GifSaveOptions
second_title: GroupDocs.Signature for Java API Reference
description: Gif format save options for Image Documents.
type: docs
weight: 15
url: /java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Gif format save options for Image Documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifSaveOptions()](#GifSaveOptions--) | Creates GifSaveOptions with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Gets or sets the GIF background color index. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Gets or sets the GIF background color index. |
| [getColorResolution()](#getColorResolution--) | Gets or sets the GIF color resolution. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Gets or sets the GIF color resolution. |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Gets or sets a value indicating whether palette correction is applied. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Gets or sets a value indicating whether palette correction is applied. |
| [hasTrailer()](#hasTrailer--) | Gets or sets a value indicating whether GIF has trailer. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Gets or sets a value indicating whether GIF has trailer. |
| [getInterlaced()](#getInterlaced--) | True if image should be interlaced. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | True if image should be interlaced. |
| [isPaletteSorted()](#isPaletteSorted--) | Gets or sets a value indicating whether palette entries are sorted. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Gets or sets a value indicating whether palette entries are sorted. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Gets or sets the GIF pixel aspect ratio. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Gets or sets the GIF pixel aspect ratio. |
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Creates GifSaveOptions with default values.

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Gets or sets the GIF background color index.

**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Gets or sets the GIF background color index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Gets or sets the GIF color resolution.

--------------------

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine.

**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Gets or sets the GIF color resolution.

--------------------

Color Resolution - Number of bits per primary color available to the original image, minus 1. This value represents the size of the entire palette from which the colors in the graphic were selected, not the number of colors actually used in the graphic. For example, if the value in this field is 3, then the palette of the original image had 4 bits per primary color available to create the image. This value should be set to indicate the richness of the original palette, even if not every color from the whole palette is available on the source machine.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Gets or sets a value indicating whether palette correction is applied.

--------------------

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.

**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Gets or sets a value indicating whether palette correction is applied.

--------------------

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Gets or sets a value indicating whether GIF has trailer.

**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Gets or sets a value indicating whether GIF has trailer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


True if image should be interlaced.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


True if image should be interlaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Gets or sets a value indicating whether palette entries are sorted.

**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Gets or sets a value indicating whether palette entries are sorted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Gets or sets the GIF pixel aspect ratio.

--------------------

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Gets or sets the GIF pixel aspect ratio.

--------------------

Pixel Aspect Ratio - Factor used to compute an approximation of the aspect ratio of the pixel in the original image. If the value of the field is not 0, this approximation of the aspect ratio is computed based on the formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 The Pixel Aspect Ratio is defined to be the quotient of the pixel's width over its height. The value range in this field allows specification of the widest pixel of 4:1 to the tallest pixel of 1:4 in increments of 1/64th. Values : 0 - No aspect ratio information is given. 1..255 - Value used in the computation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

