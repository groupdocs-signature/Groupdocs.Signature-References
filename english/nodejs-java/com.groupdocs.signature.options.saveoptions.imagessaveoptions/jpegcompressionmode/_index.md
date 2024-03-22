---
title: JpegCompressionMode
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Specifies JPEG compression modes.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Specifies JPEG compression modes.
## Fields

| Field | Description |
| --- | --- |
| [Baseline](#Baseline) | The baseline compression. |
| [Progressive](#Progressive) | The progressive compression. |
| [Lossless](#Lossless) | The lossless compression. |
| [JpegLs](#JpegLs) | The JPEG-LS compression. |
### Baseline {#Baseline}
```
public static final int Baseline
```


The baseline compression.

### Progressive {#Progressive}
```
public static final int Progressive
```


The progressive compression.

### Lossless {#Lossless}
```
public static final int Lossless
```


The lossless compression. Use this compression type carefully because many image viewers do not support it. If you use it try assign the  JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) property to [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) or [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb) values.

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


The JPEG-LS compression. Use this compression type carefully because many image viewers do not support it. If you use it try to assign the  JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) property to [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) value.

