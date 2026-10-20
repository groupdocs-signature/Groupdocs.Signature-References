---
title: "JpegCompressionMode"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "JPEG 圧縮モードを指定します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressionmode/
---
**Inheritance:**
java.lang.Object
```
public final class JpegCompressionMode
```

JPEG 圧縮モードを指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Baseline](#Baseline) | ベースライン圧縮。 |
|
|  | [Progressive](#Progressive) | プログレッシブ圧縮。 |
|
|  | [Lossless](#Lossless) | ロスレス圧縮。 |
|
|  | [JpegLs](#JpegLs) | JPEG-LS 圧縮。 |
|
### Baseline {#Baseline}
```
public static final int Baseline
```


ベースライン圧縮。


### Progressive {#Progressive}
```
public static final int Progressive
```


プログレッシブ圧縮。


### Lossless {#Lossless}
```
public static final int Lossless
```


ロスレス圧縮。この圧縮タイプは慎重に使用してください、なぜなら
多くの画像ビューアはこれをサポートしていません。使用する場合は、次のように割り当ててみてください

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) プロパティを [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale) に設定
または [JpegCompressionColorMode.Rgb](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Rgb) の値。


### JpegLs {#JpegLs}
```
public static final int JpegLs
```


JPEG-LS 圧縮。この圧縮タイプは慎重に使用してください、なぜなら
多くの画像ビューアはこれをサポートしていません。使用する場合は、次のように割り当ててみてください

JpegSaveOptions.ColorType
([JpegSaveOptions.getColorType](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#getColorType)/[JpegSaveOptions.setColorType(int)](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions#setColorType-int-)) プロパティを [JpegCompressionColorMode.Grayscale](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegcompressioncolormode#Grayscale) に設定
値。


