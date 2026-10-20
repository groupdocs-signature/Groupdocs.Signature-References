---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Specificeert JPEG-compressiemodi."
type: docs
weight: 17
url: /nl/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Specificeert JPEG-compressiemodi.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Baseline](#Baseline) | De baseline-compressie. |
|
|  | [Progressive](#Progressive) | De progressieve compressie. |
|
|  | [Lossless](#Lossless) | De verliesvrije compressie. |
|
|  | [JpegLs](#JpegLs) | De JPEG-LS-compressie. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


De baseline-compressie.


### Progressive {#Progressive}
```
public static final int Progressive
```


De progressieve compressie.


### Lossless {#Lossless}
```
public static final int Lossless
```


De verliesvrije compressie. Gebruik dit compressietype zorgvuldig omdat
veel beeldkijkers ondersteunen het niet. Als je het gebruikt, probeer dan de

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) eigenschap naar [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
of [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) waarden.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


De JPEG-LS compressie. Gebruik dit compressietype zorgvuldig omdat
veel beeldkijkers ondersteunen het niet. Als je het gebruikt, probeer toe te wijzen de

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) eigenschap naar [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
waarde.


