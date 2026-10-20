---
title: "JpegSaveOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Opciones de guardado JPEG para documentos de imagen."
type: docs
weight: 19
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Opciones de guardado JPEG para documentos de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | Crea JpegSaveOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | Obtiene o establece bits por canal para una imagen jpeg sin pérdida. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Obtiene o establece bits por canal para una imagen jpeg sin pérdida. |
|
|  | [getColorType()](#getColorType--) | Obtiene o establece el tipo de color para una imagen jpeg. |
|
|  | [setColorType(int value)](#setColorType-int-) | Obtiene o establece el tipo de color para una imagen jpeg. |
|
|  | [getComment()](#getComment--) | Obtiene o establece el comentario del archivo jpeg. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | Obtiene o establece el comentario del archivo jpeg. |
|
|  | [getCompressionType()](#getCompressionType--) | Obtiene o establece el tipo de compresión. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | Obtiene o establece el tipo de compresión. |
|
|  | [getQuality()](#getQuality--) | Obtiene o establece la calidad de la imagen. |
|
|  | [setQuality(int value)](#setQuality-int-) | Obtiene o establece la calidad de la imagen. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | Obtiene o establece el modo de redondeo de la muestra para ajustar un valor de 8 bits a un valor de n bits |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Obtiene o establece el modo de redondeo de la muestra para ajustar un valor de 8 bits a un valor de n bits |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | Obtiene o establece el formato de archivo del documento firmado. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | Obtiene o establece el formato de archivo del documento firmado. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


Crea JpegSaveOptions con valores predeterminados.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Obtiene o establece bits por canal para una imagen jpeg sin pérdida.
Ahora admitimos de 2 a 8 bits por canal.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Obtiene o establece bits por canal para una imagen jpeg sin pérdida.
Ahora admitimos de 2 a 8 bits por canal.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtiene o establece el tipo de color para una imagen jpeg.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtiene o establece el tipo de color para una imagen jpeg.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


Obtiene o establece el comentario del archivo jpeg.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Obtiene o establece el comentario del archivo jpeg.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Obtiene o establece el tipo de compresión.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Obtiene o establece el tipo de compresión.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Obtiene o establece la calidad de la imagen.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Obtiene o establece la calidad de la imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Obtiene o establece el modo de redondeo de la muestra para ajustar un valor de 8 bits a un valor de n bits
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Obtiene o establece el modo de redondeo de la muestra para ajustar un valor de 8 bits a un valor de n bits
JpegOptions.BitsPerChannel.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


Obtiene o establece el formato de archivo del documento firmado. Oculto porque no se usa en esta clase de opciones.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


Obtiene o establece el formato de archivo del documento firmado. Oculto porque no se usa en esta clase de opciones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

