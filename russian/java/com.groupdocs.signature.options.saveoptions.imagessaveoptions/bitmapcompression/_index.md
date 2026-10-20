---
title: "BitmapCompression"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Указывает различные методы сжатия растровых изображений."
type: docs
weight: 10
url: /ru/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression/
---
**Inheritance:**
java.lang.Object
```
public final class BitmapCompression
```

Указывает различные методы сжатия растровых изображений.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Rgb](#Rgb) | Без сжатия. |
|
|  | [Rle8](#Rle8) | Сжатие RLE 8‑бит/пиксель. |
|
|  | [Rle4](#Rle4) | Сжатие RLE 4‑бит/пиксель. |
|
|  | [Bitfields](#Bitfields) | Битовые поля. |
|
|  | [Jpeg](#Jpeg) | Сжатие JPEG. |
|
|  | [Png](#Png) | Сжатие PNG. |
|
### Rgb {#Rgb}
```
public static final int Rgb
```


Без сжатия.


### Rle8 {#Rle8}
```
public static final int Rle8
```


Сжатие RLE 8‑бит/пиксель. Может использоваться только с 8‑бит/пиксель битмапами.


### Rle4 {#Rle4}
```
public static final int Rle4
```


Сжатие RLE 4‑бит/пиксель. Может использоваться только с 4‑бит/пиксель битмапами.


### Bitfields {#Bitfields}
```
public static final int Bitfields
```


Битовые поля. Может использоваться только с 16‑ и 32‑бит/пиксель битмапами.


### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Сжатие JPEG. Битмап содержит изображение JPEG.


### Png {#Png}
```
public static final int Png
```


Сжатие PNG. Битмап содержит изображение PNG.


