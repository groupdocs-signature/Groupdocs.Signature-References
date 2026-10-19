---
title: "JpegCompressionMode"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحدد أوضاع ضغط JPEG."
type: docs
weight: 17
url: /ar/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

يحدد أوضاع ضغط JPEG.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Baseline](#Baseline) | ضغط الأساس. |
|
|  | [Progressive](#Progressive) | ضغط تدريجي. |
|
|  | [Lossless](#Lossless) | ضغط بدون فقدان. |
|
|  | [JpegLs](#JpegLs) | ضغط JPEG-LS. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


ضغط الأساس.


### Progressive {#Progressive}
```
public static final int Progressive
```


ضغط تدريجي.


### Lossless {#Lossless}
```
public static final int Lossless
```


ضغط بدون فقدان. استخدم هذا النوع من الضغط بحذر لأن
العديد من عارضات الصور لا تدعمها. إذا استخدمتها حاول تعيين الـ

JpegSaveOptions.ColorType
خاصية ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) إلى [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
أو قيم [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb).


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


ضغط JPEG-LS. استخدم هذا النوع من الضغط بحذر لأن
العديد من عارضات الصور لا تدعمها. إذا استخدمتها حاول تعيين الـ

JpegSaveOptions.ColorType
خاصية ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) إلى [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
القيمة.


