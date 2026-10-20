---
title: "BitmapCompression"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menentukan berbagai metode kompresi bitmap."
type: docs
weight: 10
url: /id/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Menentukan berbagai metode kompresi bitmap.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [Rgb](#Rgb) | Tidak ada kompresi. |
|
|  | [Rle8](#Rle8) | Kompresi RLE 8-bit/piksel. |
|
|  | [Rle4](#Rle4) | Kompresi RLE 4-bit/piksel. |
|
|  | [Bitfields](#Bitfields) | Bidang bit. |
|
|  | [Jpeg](#Jpeg) | Kompresi JPEG. |
|
|  | [Png](#Png) | Kompresi PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Tidak ada kompresi.


### Rle8 {#Rle8}
```
public static final int Rle8
```


Kompresi RLE 8-bit/piksel. Hanya dapat digunakan dengan bitmap 8-bit/piksel.


### Rle4 {#Rle4}
```
public static final int Rle4
```


Kompresi RLE 4-bit/piksel. Hanya dapat digunakan dengan bitmap 4-bit/piksel.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Bidang bit. Hanya dapat digunakan dengan bitmap 16 dan 32-bit/piksel.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Kompresi JPEG. Bitmap berisi gambar JPEG.


### Png {#Png}
```
public static final int Png
```


Kompresi PNG. Bitmap berisi gambar PNG.


