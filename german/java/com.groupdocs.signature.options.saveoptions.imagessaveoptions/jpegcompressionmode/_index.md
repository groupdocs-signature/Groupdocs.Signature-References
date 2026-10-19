---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Gibt JPEG-Komprimierungsmodi an."
type: docs
weight: 17
url: /de/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
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
|  | [Baseline](#Baseline) | Die Basiskompression. |
|
|  | [Progressive](#Progressive) | Die progressive Kompression. |
|
|  | [Lossless](#Lossless) | Die verlustfreie Kompression. |
|
|  | [JpegLs](#JpegLs) | Die JPEG-LS-Kompression. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


Die Basiskompression.


### Progressive {#Progressive}
```
public static final int Progressive
```


Die progressive Kompression.


### Lossless {#Lossless}
```
public static final int Lossless
```


Die verlustfreie Kompression. Verwenden Sie diesen Kompressionstyp vorsichtig, weil
Viele Bildbetrachter unterstützen es nicht. Wenn Sie es verwenden, versuchen Sie, das

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) Eigenschaft zu [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
oder [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) Werte.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Die JPEG-LS-Kompression. Verwenden Sie diesen Kompressionstyp vorsichtig, weil
Viele Bildbetrachter unterstützen es nicht. Wenn Sie es verwenden, versuchen Sie, das zuzuweisen

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) Eigenschaft zu [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
Wert.


