---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحدد أوضاع ضغط JPEG."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
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
| [Baseline](#Baseline) | ضغط الخط الأساسي. |
| [Progressive](#Progressive) | ضغط تدريجي. |
| [Lossless](#Lossless) | ضغط بدون فقدان. |
| [JpegLs](#JpegLs) | ضغط JPEG-LS. |
### Baseline {#Baseline}
```
public static final int Baseline
```


ضغط الخط الأساسي.

### Progressive {#Progressive}
```
public static final int Progressive
```


ضغط تدريجي.

### Lossless {#Lossless}
```
public static final int Lossless
```


ضغط بدون فقدان. استخدم هذا النوع من الضغط بحذر لأن العديد من عارضات الصور لا تدعمه. إذا استخدمته، حاول تعيين خاصية JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) إلى القيم [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) أو [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb).

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


ضغط JPEG-LS. استخدم هذا النوع من الضغط بحذر لأن العديد من عارضات الصور لا تدعمه. إذا استخدمته، حاول تعيين خاصية JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) إلى القيمة [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale).

