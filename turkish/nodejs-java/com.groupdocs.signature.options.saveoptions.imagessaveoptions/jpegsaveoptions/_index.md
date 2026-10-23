---
title: "JpegSaveOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Görüntü Belgeleri için JPEG kaydetme seçenekleri."
type: docs
weight: 19
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

Görüntü Belgeleri için JPEG kaydetme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [JpegSaveOptions()](#JpegSaveOptions--) | JpegSaveOptions'ı varsayılan değerlerle oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerChannel()](#getBitsPerChannel--) | kayıpsız jpeg görüntüsü için kanal başına bit sayısını alır veya ayarlar. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | kayıpsız jpeg görüntüsü için kanal başına bit sayısını alır veya ayarlar. |
| [getColorType()](#getColorType--) | jpeg görüntüsü için renk tipini alır veya ayarlar. |
| [setColorType(int value)](#setColorType-int-) | jpeg görüntüsü için renk tipini alır veya ayarlar. |
| [getComment()](#getComment--) | jpeg dosya yorumunu alır veya ayarlar. |
| [setComment(String value)](#setComment-java.lang.String-) | jpeg dosya yorumunu alır veya ayarlar. |
| [getCompressionType()](#getCompressionType--) | sıkıştırma tipini alır veya ayarlar. |
| [setCompressionType(int value)](#setCompressionType-int-) | sıkıştırma tipini alır veya ayarlar. |
| [getQuality()](#getQuality--) | görüntü kalitesini alır veya ayarlar. |
| [setQuality(int value)](#setQuality-int-) | görüntü kalitesini alır veya ayarlar. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | 8-bit değeri n-bit değere uydurmak için örnek yuvarlama modunu JpegOptions.BitsPerChannel alır veya ayarlar. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8-bit değeri n-bit değere uydurmak için örnek yuvarlama modunu JpegOptions.BitsPerChannel alır veya ayarlar. |
| [getFileFormat()](#getFileFormat--) | İmzalı belgenin dosya formatını alır veya ayarlar. |
| [setFileFormat(int value)](#setFileFormat-int-) | İmzalı belgenin dosya formatını alır veya ayarlar. |
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


JpegSaveOptions'ı varsayılan değerlerle oluşturur.

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


kayıpsız jpeg görüntüsü için kanal başına bit sayısını alır veya ayarlar. Şimdi 2 ile 8 bit arasında kanal başına desteklenmektedir.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


kayıpsız jpeg görüntüsü için kanal başına bit sayısını alır veya ayarlar. Şimdi 2 ile 8 bit arasında kanal başına desteklenmektedir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg görüntüsü için renk tipini alır veya ayarlar.

**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg görüntüsü için renk tipini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


jpeg dosya yorumunu alır veya ayarlar.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpeg dosya yorumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


sıkıştırma tipini alır veya ayarlar.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


sıkıştırma tipini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


görüntü kalitesini alır veya ayarlar.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


görüntü kalitesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8-bit değeri n-bit değere uydurmak için örnek yuvarlama modunu JpegOptions.BitsPerChannel alır veya ayarlar.

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8-bit değeri n-bit değere uydurmak için örnek yuvarlama modunu JpegOptions.BitsPerChannel alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


İmzalı belgenin dosya formatını alır veya ayarlar. Bu seçenek sınıfı için kullanılmadığından gizlidir.

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


İmzalı belgenin dosya formatını alır veya ayarlar. Bu seçenek sınıfı için kullanılmadığından gizlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

