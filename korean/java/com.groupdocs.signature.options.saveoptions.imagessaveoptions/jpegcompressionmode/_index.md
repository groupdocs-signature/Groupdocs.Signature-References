---
title: "JpegCompressionMode"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "JPEG 압축 모드를 지정합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

JPEG 압축 모드를 지정합니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Baseline](#Baseline) | 기본 압축. |
|
|  | [Progressive](#Progressive) | 프로그레시브 압축. |
|
|  | [Lossless](#Lossless) | 무손실 압축. |
|
|  | [JpegLs](#JpegLs) | JPEG-LS 압축. |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


기본 압축.


### Progressive {#Progressive}
```
public static final int Progressive
```


프로그레시브 압축.


### Lossless {#Lossless}
```
public static final int Lossless
```


무손실 압축. 이 압축 유형을 신중하게 사용하십시오, 왜냐하면
많은 이미지 뷰어가 이를 지원하지 않습니다. 사용하려면 다음을 할당해 보세요

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) 속성에 [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
또는 [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) 값.


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


JPEG-LS 압축. 이 압축 유형을 신중하게 사용하십시오, 왜냐하면
많은 이미지 뷰어가 이를 지원하지 않습니다. 사용하려면 다음을 할당해 보세요

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) 속성에 [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale)
값.


