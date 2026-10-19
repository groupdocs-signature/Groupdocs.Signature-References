---
title: "BitmapCompression"
second_title: "Αναφορά API του GroupDocs.Signature για Java"
description: "Καθορίζει διαφορετικές μεθόδους συμπίεσης bitmap."
type: docs
weight: 10
url: /el/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Καθορίζει διαφορετικές μεθόδους συμπίεσης bitmap.

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [Rgb](#Rgb) | Χωρίς συμπίεση. |
|
|  | [Rle8](#Rle8) | Συμπίεση RLE 8-bit/pixel. |
|
|  | [Rle4](#Rle4) | Συμπίεση RLE 4-bit/pixel. |
|
|  | [Bitfields](#Bitfields) | Πεδία bit. |
|
|  | [Jpeg](#Jpeg) | Συμπίεση JPEG. |
|
|  | [Png](#Png) | Συμπίεση PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Χωρίς συμπίεση.


### Rle8 {#Rle8}
```
public static final int Rle8
```


Συμπίεση RLE 8-bit/pixel. Μπορεί να χρησιμοποιηθεί μόνο με bitmap 8-bit/pixel.


### Rle4 {#Rle4}
```
public static final int Rle4
```


Συμπίεση RLE 4-bit/pixel. Μπορεί να χρησιμοποιηθεί μόνο με bitmap 4-bit/pixel.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Πεδία bit. Μπορεί να χρησιμοποιηθεί μόνο με bitmap 16 και 32-bit/pixel.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Συμπίεση JPEG. Το bitmap περιέχει εικόνα JPEG.


### Png {#Png}
```
public static final int Png
```


Συμπίεση PNG. Το bitmap περιέχει εικόνα PNG.


