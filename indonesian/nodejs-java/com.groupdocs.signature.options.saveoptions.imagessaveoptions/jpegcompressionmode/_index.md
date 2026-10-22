---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature untuk Node.js via Referensi API Java"
description: "Menentukan mode kompresi JPEG."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Menentukan mode kompresi JPEG.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [Baseline](#Baseline) | Kompresi baseline. |
| [Progressive](#Progressive) | Kompresi progresif. |
| [Lossless](#Lossless) | Kompresi lossless. |
| [JpegLs](#JpegLs) | Kompresi JPEG-LS. |
### Baseline {#Baseline}
```
public static final int Baseline
```


Kompresi baseline.

### Progressive {#Progressive}
```
public static final int Progressive
```


Kompresi progresif.

### Lossless {#Lossless}
```
public static final int Lossless
```


Kompresi lossless. Gunakan tipe kompresi ini dengan hati-hati karena banyak penampil gambar tidak mendukungnya. Jika Anda menggunakannya, coba tetapkan properti JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\\#setColorType-int-)) ke nilai [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\\#Grayscale) atau [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\\#Rgb).

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Kompresi JPEG-LS. Gunakan tipe kompresi ini dengan hati-hati karena banyak penampil gambar tidak mendukungnya. Jika Anda menggunakannya, coba tetapkan properti JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\\#setColorType-int-)) ke nilai [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\\#Grayscale).

