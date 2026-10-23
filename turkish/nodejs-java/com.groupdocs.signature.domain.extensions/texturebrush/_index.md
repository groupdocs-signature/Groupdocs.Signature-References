---
title: "TextureBrush"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Doku fırçasını temsil eder."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions/texturebrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class TextureBrush extends Brush
```

Doku fırçasını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextureBrush()](#TextureBrush--) | TextureBrush sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [TextureBrush(String imageFilePath)](#TextureBrush-java.lang.String-) | TextureBrush sınıfının yeni bir örneğini görüntü dosyasıyla başlatır. |
| [TextureBrush(InputStream imageStream)](#TextureBrush-java.io.InputStream-) | TextureBrush sınıfının yeni bir örneğini görüntü akışı seçeneğiyle başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getImageFilePath()](#getImageFilePath--) | Doku görüntü dosyası yolunu alır veya ayarlar. |
| [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | Doku görüntü dosyası yolunu alır veya ayarlar. |
| [getImageStream()](#getImageStream--) | Doku görüntü akışını alır veya ayarlar. |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | Doku görüntü akışını alır veya ayarlar. |
### TextureBrush() {#TextureBrush--}
```
public TextureBrush()
```


TextureBrush sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### TextureBrush(String imageFilePath) {#TextureBrush-java.lang.String-}
```
public TextureBrush(String imageFilePath)
```


TextureBrush sınıfının yeni bir örneğini görüntü dosyasıyla başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageFilePath | java.lang.String | Görüntü dosyası yolu. |

### TextureBrush(InputStream imageStream) {#TextureBrush-java.io.InputStream-}
```
public TextureBrush(InputStream imageStream)
```


TextureBrush sınıfının yeni bir örneğini görüntü akışı seçeneğiyle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageStream | java.io.InputStream | Görüntü akışı. |

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


Doku görüntü dosyası yolunu alır veya ayarlar. Bu özellik yalnızca ImageStream belirtilmemişse kullanılır.

**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


Doku görüntü dosyası yolunu alır veya ayarlar. Bu özellik yalnızca ImageStream belirtilmemişse kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


Doku görüntü akışını alır veya ayarlar. Bu özellik belirtilirse her zaman ImageFilePath yerine kullanılır.

**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


Doku görüntü akışını alır veya ayarlar. Bu özellik belirtilirse her zaman ImageFilePath yerine kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.io.InputStream |  |

