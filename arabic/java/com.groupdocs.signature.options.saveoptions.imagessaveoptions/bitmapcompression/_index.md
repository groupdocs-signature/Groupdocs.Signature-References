---
title: "BitmapCompression"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحدد طرق ضغط البت ماب المختلفة."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

يحدد طرق ضغط البت ماب المختلفة.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Rgb](#Rgb) | بدون ضغط. |
|
|  | [Rle8](#Rle8) | ضغط RLE 8-بت/بكسل. |
|
|  | [Rle4](#Rle4) | ضغط RLE 4-بت/بكسل. |
|
|  | [Bitfields](#Bitfields) | حقول بت. |
|
|  | [Jpeg](#Jpeg) | ضغط JPEG. |
|
|  | [Png](#Png) | ضغط PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


بدون ضغط.


### Rle8 {#Rle8}
```
public static final int Rle8
```


ضغط RLE 8-بت/بكسل. يمكن استخدامه فقط مع صور bitmap 8-بت/بكسل.


### Rle4 {#Rle4}
```
public static final int Rle4
```


ضغط RLE 4-بت/بكسل. يمكن استخدامه فقط مع صور bitmap 4-بت/بكسل.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


حقول بت. يمكن استخدامها فقط مع صور bitmap 16 و 32-بت/بكسل.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


ضغط JPEG. يحتوي bitmap على صورة JPEG.


### Png {#Png}
```
public static final int Png
```


ضغط PNG. يحتوي bitmap على صورة PNG.


