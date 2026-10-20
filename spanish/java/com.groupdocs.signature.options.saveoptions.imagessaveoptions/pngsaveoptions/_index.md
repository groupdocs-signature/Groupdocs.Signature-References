---
title: "PngSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado PNG para documentos de imagen."
type: docs
weight: 22
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Opciones de guardado PNG para documentos de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | Crea PngSaveOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | La profundidad de bits. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | La profundidad de bits. |
|
|  | [getColorType()](#getColorType--) | Obtiene o establece el tipo de |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | Obtiene o establece el tipo de |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima |
y 0 es modo de almacenamiento.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima |
y 0 es modo de almacenamiento.
|
|  | [getFilterType()](#getFilterType--) | Obtiene o establece el tipo de filtro |
PngFilterType
utilizado durante el proceso de guardado del archivo png.
|
|  | [setFilterType(int value)](#setFilterType-int-) | Obtiene o establece el tipo de filtro |
PngFilterType
utilizado durante el proceso de guardado del archivo png.
|
|  | [getProgressive()](#getProgressive--) | Obtiene o establece un valor que indica si este PngSaveOptions es progresivo. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | Obtiene o establece un valor que indica si este PngSaveOptions es progresivo. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


Crea PngSaveOptions con valores predeterminados.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


La profundidad de bits.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


La profundidad de bits.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtiene o establece el tipo de
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtiene o establece el tipo de
PngColorType
.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima
y 0 es modo de almacenamiento.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima
y 0 es modo de almacenamiento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Obtiene o establece el tipo de filtro
PngFilterType
utilizado durante el proceso de guardado del archivo png.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Obtiene o establece el tipo de filtro
PngFilterType
utilizado durante el proceso de guardado del archivo png.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Obtiene o establece un valor que indica si este PngSaveOptions es progresivo.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Obtiene o establece un valor que indica si este PngSaveOptions es progresivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

