---
title: "JpegCompressionMode"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Menentukan mode kompresi JPEG."
type: docs
weight: 17
url: /id/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
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
|  | [Baseline](#Baseline) | Kompressi dasar. |
|
|  | [Progressive](#Progressive) | Kompressi progresif. |
|
|  | [Lossless](#Lossless) | Kompressi tanpa kehilangan. |
|
|  | [JpegLs](#JpegLs) | Kompressi JPEG-LS. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


Kompressi dasar.


### Progressive {#Progressive}
```
public static final int Progressive
```


Kompressi progresif.


### Lossless {#Lossless}
```
public static final int Lossless
```


Kompressi tanpa kehilangan. Gunakan tipe kompresi ini dengan hati-hati karena
banyak penampil gambar tidak mendukungnya. Jika Anda menggunakannya, coba tetapkan

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) properti ke [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
atau [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) nilai.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Kompressi JPEG-LS. Gunakan tipe kompresi ini dengan hati-hati karena
banyak penampil gambar tidak mendukungnya. Jika Anda menggunakannya, coba tetapkan

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) properti ke [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
nilai.


