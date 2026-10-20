---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Anger JPEG-komprimeringslägen."
type: docs
weight: 17
url: /sv/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Anger JPEG-komprimeringslägen.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Baseline](#Baseline) | Den grundläggande komprimeringen. |
|
|  | [Progressive](#Progressive) | Den progressiva komprimeringen. |
|
|  | [Lossless](#Lossless) | Den förlustfria komprimeringen. |
|
|  | [JpegLs](#JpegLs) | Den JPEG-LS-komprimeringen. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


Den grundläggande komprimeringen.


### Progressive {#Progressive}
```
public static final int Progressive
```


Den progressiva komprimeringen.


### Lossless {#Lossless}
```
public static final int Lossless
```


Den förlustfria komprimeringen. Använd den här komprimeringstypen försiktigt eftersom
många bildvisare stöder den inte. Om du använder den, försök tilldela

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) egenskap till [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
eller [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) värden.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Den JPEG-LS-komprimeringen. Använd den här komprimeringstypen försiktigt eftersom
många bildvisare stöder den inte. Om du använder den, försök att tilldela den

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) egenskap till [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
värde.


