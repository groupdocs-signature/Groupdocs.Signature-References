---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature für Node.js über Java API-Referenz"
description: "Gibt JPEG-Komprimierungsmodi an."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Gibt JPEG-Komprimierungsmodi an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Baseline](#Baseline) | Die Basiskomprimierung. |
| [Progressive](#Progressive) | Die progressive Komprimierung. |
| [Lossless](#Lossless) | Die verlustfreie Komprimierung. |
| [JpegLs](#JpegLs) | Die JPEG-LS-Komprimierung. |
### Baseline {#Baseline}
```
public static final int Baseline
```


Die Basiskomprimierung.

### Progressive {#Progressive}
```
public static final int Progressive
```


Die progressive Komprimierung.

### Lossless {#Lossless}
```
public static final int Lossless
```


Die verlustfreie Komprimierung. Verwenden Sie diesen Komprimierungstyp vorsichtig, weil viele Bildbetrachter ihn nicht unterstützen. Wenn Sie ihn verwenden, versuchen Sie, die JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) Eigenschaft auf die Werte [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) oder [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb) zuweisen.

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Die JPEG-LS-Komprimierung. Verwenden Sie diesen Komprimierungstyp vorsichtig, weil viele Bildbetrachter ihn nicht unterstützen. Wenn Sie ihn verwenden, versuchen Sie, die JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) Eigenschaft auf den Wert [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) zu setzen.

