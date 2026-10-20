---
title: "TextureBrush"
second_title: "Referensi API GroupDocs.Signature untuk Java"
description: "Mewakili kuas tekstur."
type: docs
weight: 14
url: /id/java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Mewakili kuas tekstur.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [TextureBrush()](#TextureBrush--) | Menginisialisasi instance baru dari kelas TextureBrush dengan nilai default. |
|
|  | [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | Menginisialisasi instance baru dari kelas TextureBrush dengan file gambar. |
|
|  | [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | Menginisialisasi instance baru dari kelas TextureBrush dengan opsi aliran gambar. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | Mendapatkan atau mengatur jalur file gambar tekstur. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Mendapatkan atau mengatur jalur file gambar tekstur. |
|
|  | [getImageStream()](#getImageStream--) | Mendapatkan atau mengatur aliran gambar tekstur. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Mendapatkan atau mengatur aliran gambar tekstur. |
|
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


Menginisialisasi instance baru dari kelas TextureBrush dengan nilai default.


### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


Menginisialisasi instance baru dari kelas TextureBrush dengan file gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Jalur file gambar. |
|

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


Menginisialisasi instance baru dari kelas TextureBrush dengan opsi aliran gambar.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Aliran gambar. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Mendapatkan atau mengatur jalur file gambar tekstur.
Properti ini hanya digunakan jika ImageStream tidak ditentukan.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Mendapatkan atau mengatur jalur file gambar tekstur.
Properti ini hanya digunakan jika ImageStream tidak ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Mendapatkan atau mengatur aliran gambar tekstur.
Jika properti ini ditentukan, selalu digunakan menggantikan ImageFilePath.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Mendapatkan atau mengatur aliran gambar tekstur.
Jika properti ini ditentukan, selalu digunakan menggantikan ImageFilePath.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.io.InputStream |  |

