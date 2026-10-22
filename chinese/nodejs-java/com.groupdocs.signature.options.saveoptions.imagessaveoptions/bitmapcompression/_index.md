---
title: "BitmapCompression"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "指定不同的位图压缩方法。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

指定不同的位图压缩方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Rgb](#Rgb) | 无压缩。 |
| [Rle8](#Rle8) | RLE 8 位/像素 压缩。 |
| [Rle4](#Rle4) | RLE 4 位/像素 压缩。 |
| [Bitfields](#Bitfields) | 位字段。 |
| [Jpeg](#Jpeg) | JPEG 压缩。 |
| [Png](#Png) | PNG 压缩。 |
### Rgb {#Rgb}
```
public static final int Rgb
```


无压缩。

### Rle8 {#Rle8}
```
public static final int Rle8
```


RLE 8 位/像素 压缩。只能用于 8 位/像素 位图。

### Rle4 {#Rle4}
```
public static final int Rle4
```


RLE 4 位/像素 压缩。只能用于 4 位/像素 位图。

### Bitfields {#Bitfields}
```
public static final int Bitfields
```


位字段。只能与 16 位和 32 位/像素 位图一起使用。

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


JPEG 压缩。位图包含 JPEG 图像。

### Png {#Png}
```
public static final int Png
```


PNG 压缩。位图包含 PNG 图像。

