---
title: "JpegCompressionMode"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Указывает режимы сжатия JPEG."
type: docs
weight: 17
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

Указывает режимы сжатия JPEG.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Baseline](#Baseline) | Базовое сжатие. |
|
|  | [Progressive](#Progressive) | Прогрессивное сжатие. |
|
|  | [Lossless](#Lossless) | Сжатие без потерь. |
|
|  | [JpegLs](#JpegLs) | Сжатие JPEG-LS. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


Базовое сжатие.


### Progressive {#Progressive}
```
public static final int Progressive
```


Прогрессивное сжатие.


### Lossless {#Lossless}
```
public static final int Lossless
```


Сжатие без потерь. Используйте этот тип сжатия осторожно, потому что
многие просмотрщики изображений не поддерживают его. Если вы используете его, попробуйте назначить это

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) свойство к [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
или значения [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb).


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


Сжатие JPEG-LS. Используйте этот тип сжатия осторожно, потому что
многие просмотрщики изображений не поддерживают его. Если вы используете его, попробуйте назначить это

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) свойство к [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
значение.


