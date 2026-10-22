---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "指定 JPEG 压缩模式。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

指定 JPEG 压缩模式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Baseline](#Baseline) | 基线压缩。 |
| [Progressive](#Progressive) | 渐进式压缩。 |
| [Lossless](#Lossless) | 无损压缩。 |
| [JpegLs](#JpegLs) | JPEG-LS 压缩。 |
### Baseline {#Baseline}
```
public static final int Baseline
```


基线压缩。

### Progressive {#Progressive}
```
public static final int Progressive
```


渐进式压缩。

### Lossless {#Lossless}
```
public static final int Lossless
```


无损压缩。请谨慎使用此压缩类型，因为许多图像查看器不支持它。如果使用，请尝试将 JpegSaveOptions.ColorType（[JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-))属性设置为 [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) 或 [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Rgb) 值。

### JpegLs {#JpegLs}
```
public static final int JpegLs
```


JPEG-LS 压缩。请谨慎使用此压缩类型，因为许多图像查看器不支持它。如果使用，请尝试将 JpegSaveOptions.ColorType（[JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions\#setColorType-int-))属性设置为 [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode\#Grayscale) 值。

