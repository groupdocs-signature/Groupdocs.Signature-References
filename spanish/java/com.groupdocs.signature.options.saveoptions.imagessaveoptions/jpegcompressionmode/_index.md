---
title: "JpegCompressionMode"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Especifica modos de compresión JPEG."
type: docs
weight: 17
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Especifica modos de compresión JPEG.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Baseline](#Baseline) | La compresión básica. |
|
|  | [Progressive](#Progressive) | La compresión progresiva. |
|
|  | [Lossless](#Lossless) | La compresión sin pérdida. |
|
|  | [JpegLs](#JpegLs) | La compresión JPEG-LS. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


La compresión básica.


### Progressive {#Progressive}
```
public static final int Progressive
```


La compresión progresiva.


### Lossless {#Lossless}
```
public static final int Lossless
```


La compresión sin pérdida. Use este tipo de compresión con cuidado porque
muchos visores de imágenes no lo soportan. Si lo usa, intente asignar el

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) propiedad a [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
o [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) valores.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


La compresión JPEG-LS. Use este tipo de compresión con cuidado porque
muchos visores de imágenes no lo soportan. Si lo usa, intente asignar el

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) propiedad a [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
valor.


