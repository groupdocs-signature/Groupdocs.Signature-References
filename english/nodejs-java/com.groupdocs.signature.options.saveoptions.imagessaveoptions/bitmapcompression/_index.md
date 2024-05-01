---
title: BitmapCompression
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Specifies different bitmap compression methods.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Specifies different bitmap compression methods.
## Fields

| Field | Description |
| --- | --- |
| [Rgb](#Rgb) | No compression. |
| [Rle8](#Rle8) | RLE 8-bit/pixel compression. |
| [Rle4](#Rle4) | RLE 4-bit/pixel compression. |
| [Bitfields](#Bitfields) | Bit fields. |
| [Jpeg](#Jpeg) | JPEG compression. |
| [Png](#Png) | PNG compression. |
### Rgb {#Rgb}
```
public static final int Rgb
```


No compression.

### Rle8 {#Rle8}
```
public static final int Rle8
```


RLE 8-bit/pixel compression. Can be used only with 8-bit/pixel bitmaps.

### Rle4 {#Rle4}
```
public static final int Rle4
```


RLE 4-bit/pixel compression. Can be used only with 4-bit/pixel bitmaps.

### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Bit fields. Can be used only with 16 and 32-bit/pixel bitmaps.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


JPEG compression. The bitmap contains a JPEG image.

### Png {#Png}
```
public static final int Png
```


PNG compression. The bitmap contains a PNG image.

