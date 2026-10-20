---
title: "BmpSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado BMP para documentos de imagen."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

Opciones de guardado BMP para documentos de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | Crea BmpSaveOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene o establece la cantidad de bits por píxel de la imagen. |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Obtiene o establece la cantidad de bits por píxel de la imagen. |
|
|  | [getCompression()](#getCompression--) | Obtiene o establece la compresión. |
|
|  | [setCompression(int value)](#setCompression-int-) | Obtiene o establece la compresión. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene o establece la resolución horizontal. |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtiene o establece la resolución horizontal. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Obtiene o establece la resolución vertical. |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtiene o establece la resolución vertical. |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


Crea BmpSaveOptions con valores predeterminados.


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


Obtiene o establece la cantidad de bits por píxel de la imagen.


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


Obtiene o establece la cantidad de bits por píxel de la imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Obtiene o establece la compresión. Ver [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Obtiene o establece la compresión. Ver [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


Obtiene o establece la resolución horizontal. Nota: debido al redondeo, el resultado
la resolución puede diferir ligeramente de la proporcionada.


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


Obtiene o establece la resolución horizontal. Nota: debido al redondeo, el resultado
la resolución puede diferir ligeramente de la proporcionada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


Obtiene o establece la resolución vertical. Nota: debido al redondeo, el resultado
la resolución puede diferir ligeramente de la proporcionada.


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


Obtiene o establece la resolución vertical. Nota: debido al redondeo, el resultado
la resolución puede diferir ligeramente de la proporcionada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

