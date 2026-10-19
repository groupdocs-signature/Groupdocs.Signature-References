---
title: "BitmapCompression"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Spécifie différentes méthodes de compression bitmap."
type: docs
weight: 10
url: /fr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Spécifie différentes méthodes de compression bitmap.

## Champs

| Champ | Description |
| --- | --- |
|  | [Rgb](#Rgb) | Pas de compression. |
|
|  | [Rle8](#Rle8) | Compression RLE 8 bits/pixel. |
|
|  | [Rle4](#Rle4) | Compression RLE 4 bits/pixel. |
|
|  | [Bitfields](#Bitfields) | Champs de bits. |
|
|  | [Jpeg](#Jpeg) | Compression JPEG. |
|
|  | [Png](#Png) | Compression PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Pas de compression.


### Rle8 {#Rle8}
```
public static final int Rle8
```


Compression RLE 8 bits/pixel. Ne peut être utilisée que avec des images bitmap 8 bits/pixel.


### Rle4 {#Rle4}
```
public static final int Rle4
```


Compression RLE 4 bits/pixel. Ne peut être utilisée que avec des images bitmap 4 bits/pixel.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Champs de bits. Ne peut être utilisée que avec des images bitmap 16 et 32 bits/pixel.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Compression JPEG. Le bitmap contient une image JPEG.


### Png {#Png}
```
public static final int Png
```


Compression PNG. Le bitmap contient une image PNG.


