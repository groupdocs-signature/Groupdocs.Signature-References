---
title: "BitmapCompression"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Specifica diversi metodi di compressione bitmap."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Specifica diversi metodi di compressione bitmap.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Rgb](#Rgb) | Nessuna compressione. |
|
|  | [Rle8](#Rle8) | Compressione RLE a 8 bit/pixel. |
|
|  | [Rle4](#Rle4) | Compressione RLE a 4 bit/pixel. |
|
|  | [Bitfields](#Bitfields) | Campi di bit. |
|
|  | [Jpeg](#Jpeg) | Compressione JPEG. |
|
|  | [Png](#Png) | Compressione PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Nessuna compressione.


### Rle8 {#Rle8}
```
public static final int Rle8
```


Compressione RLE a 8 bit/pixel. Può essere usata solo con bitmap a 8 bit/pixel.


### Rle4 {#Rle4}
```
public static final int Rle4
```


Compressione RLE a 4 bit/pixel. Può essere usata solo con bitmap a 4 bit/pixel.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Campi di bit. Può essere usato solo con bitmap a 16 e 32 bit/pixel.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Compressione JPEG. Il bitmap contiene un'immagine JPEG.


### Png {#Png}
```
public static final int Png
```


Compressione PNG. Il bitmap contiene un'immagine PNG.


