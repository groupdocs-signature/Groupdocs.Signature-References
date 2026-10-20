---
title: "BitmapCompression"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Especifica diferentes métodos de compresión de mapas de bits."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Especifica diferentes métodos de compresión de mapas de bits.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Rgb](#Rgb) | Sin compresión. |
|
|  | [Rle8](#Rle8) | Compresión RLE de 8 bits/píxel. |
|
|  | [Rle4](#Rle4) | Compresión RLE de 4 bits/píxel. |
|
|  | [Bitfields](#Bitfields) | Campos de bits. |
|
|  | [Jpeg](#Jpeg) | Compresión JPEG. |
|
|  | [Png](#Png) | Compresión PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Sin compresión.


### Rle8 {#Rle8}
```
public static final int Rle8
```


Compresión RLE de 8 bits/píxel. Solo se puede usar con mapas de bits de 8 bits/píxel.


### Rle4 {#Rle4}
```
public static final int Rle4
```


Compresión RLE de 4 bits/píxel. Solo se puede usar con mapas de bits de 4 bits/píxel.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Campos de bits. Solo se pueden usar con mapas de bits de 16 y 32 bits/píxel.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Compresión JPEG. El mapa de bits contiene una imagen JPEG.


### Png {#Png}
```
public static final int Png
```


Compresión PNG. El mapa de bits contiene una imagen PNG.


