---
title: "BitmapCompression"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Specificeert verschillende bitmap-compressiemethoden."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Specificeert verschillende bitmap-compressiemethoden.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Rgb](#Rgb) | Geen compressie. |
|
|  | [Rle8](#Rle8) | RLE 8-bit/pixel compressie. |
|
|  | [Rle4](#Rle4) | RLE 4-bit/pixel compressie. |
|
|  | [Bitfields](#Bitfields) | Bitvelden. |
|
|  | [Jpeg](#Jpeg) | JPEG-compressie. |
|
|  | [Png](#Png) | PNG-compressie. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Geen compressie.


### Rle8 {#Rle8}
```
public static final int Rle8
```


RLE 8-bit/pixel compressie. Kan alleen worden gebruikt met 8-bit/pixel bitmapafbeeldingen.


### Rle4 {#Rle4}
```
public static final int Rle4
```


RLE 4-bit/pixel compressie. Kan alleen worden gebruikt met 4-bit/pixel bitmapafbeeldingen.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Bitvelden. Kan alleen worden gebruikt met 16- en 32-bit/pixel bitmapafbeeldingen.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


JPEG-compressie. De bitmap bevat een JPEG-afbeelding.


### Png {#Png}
```
public static final int Png
```


PNG-compressie. De bitmap bevat een PNG-afbeelding.


