---
title: "JpegCompressionMode"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "JPEG sıkıştırma modlarını belirtir."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

JPEG sıkıştırma modlarını belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Baseline](#Baseline) | Temel sıkıştırma. |
| [Progressive](#Progressive) | İlerlemeli sıkıştırma. |
| [Lossless](#Lossless) | Kayıpsız sıkıştırma. |
| [JpegLs](#JpegLs) | JPEG-LS sıkıştırması. |
### Baseline {#Baseline}
```
public static final int Baseline
```


Temel sıkıştırma.

### Progressive {#Progressive}
```
public static final int Progressive
```


İlerlemeli sıkıştırma.

### Lossless {#Lossless}
```
public static final int Lossless
```


Kayıpsız sıkıştırma. Bu sıkıştırma türünü dikkatli kullanın çünkü birçok görüntü görüntüleyicisi bunu desteklemez. Eğer kullanıyorsanız JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) özelliğini [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) veya [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb) değerlerine atamayı deneyin.

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


JPEG-LS sıkıştırması. Bu sıkıştırma türünü dikkatli kullanın çünkü birçok görüntü görüntüleyicisi bunu desteklemez. Eğer kullanıyorsanız JpegSaveOptions.ColorType ([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-)) özelliğini [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) değerine atamayı deneyin.

