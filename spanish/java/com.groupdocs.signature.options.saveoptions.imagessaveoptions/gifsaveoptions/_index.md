---
title: "GifSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado en formato GIF para documentos de imagen."
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Opciones de guardado en formato GIF para documentos de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | Crea GifSaveOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Obtiene o establece el índice de color de fondo del GIF. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Obtiene o establece el índice de color de fondo del GIF. |
|
|  | [getColorResolution()](#getColorResolution--) | Obtiene o establece la resolución de color del GIF. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | Obtiene o establece la resolución de color del GIF. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
|
|  | [hasTrailer()](#hasTrailer--) | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
|
|  | [getInterlaced()](#getInterlaced--) | Verdadero si la imagen debe estar entrelazada. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | Verdadero si la imagen debe estar entrelazada. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | Obtiene o establece la relación de aspecto de píxel del GIF. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Obtiene o establece la relación de aspecto de píxel del GIF. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


Crea GifSaveOptions con valores predeterminados.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Obtiene o establece el índice de color de fondo del GIF.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Obtiene o establece el índice de color de fondo del GIF.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Obtiene o establece la resolución de color del GIF.

<br />

*** ** * ** ***

Resolución de color - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente utilizados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina fuente.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Obtiene o establece la resolución de color del GIF.

<br />

*** ** * ** ***

Resolución de color - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente utilizados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina fuente.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Obtiene o establece un valor que indica si se aplica la corrección de paleta.

<br />

*** ** * ** ***

La corrección de paleta significa que cada vez que la imagen se exporta a GIF, los colores de la imagen origen serán analizados para construir la paleta que mejor coincida (en caso de que la paleta de la imagen no exista o no se haya especificado en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen resultante tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Obtiene o establece un valor que indica si se aplica la corrección de paleta.

<br />

*** ** * ** ***

La corrección de paleta significa que cada vez que la imagen se exporta a GIF, los colores de la imagen origen serán analizados para construir la paleta que mejor coincida (en caso de que la paleta de la imagen no exista o no se haya especificado en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen resultante tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Obtiene o establece un valor que indica si el GIF tiene tráiler.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Obtiene o establece un valor que indica si el GIF tiene tráiler.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Verdadero si la imagen debe estar entrelazada.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Verdadero si la imagen debe estar entrelazada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Obtiene o establece la relación de aspecto de píxel del GIF.

<br />

*** ** * ** ***

Relación de aspecto de píxel - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula según la fórmula: Relación de aspecto = (Relación de aspecto de píxel + 15) / 64. La relación de aspecto de píxel se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor utilizado en el cálculo.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Obtiene o establece la relación de aspecto de píxel del GIF.

<br />

*** ** * ** ***

Relación de aspecto de píxel - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula según la fórmula: Relación de aspecto = (Relación de aspecto de píxel + 15) / 64. La relación de aspecto de píxel se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor utilizado en el cálculo.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

