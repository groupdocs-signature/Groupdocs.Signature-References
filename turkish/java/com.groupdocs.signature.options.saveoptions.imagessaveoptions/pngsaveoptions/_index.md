---
title: "PngSaveOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Görüntü Belgeleri için Png kaydetme seçenekleri."
type: docs
weight: 22
url: /tr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

Görüntü Belgeleri için Png kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | Varsayılan değerlerle PngSaveOptions oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | Bit derinliği. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | Bit derinliği. |
|
|  | [getColorType()](#getColorType--) | Türünü alır veya ayarlar |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | Türünü alır veya ayarlar |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | 0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma seviyesidir |
ve 0 depolama modudur.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | 0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma seviyesidir |
ve 0 depolama modudur.
|
|  | [getFilterType()](#getFilterType--) | Filtre tipini alır veya ayarlar |
PngFilterType
png dosyası kaydetme sürecinde kullanılır.
|
|  | [setFilterType(int value)](#setFilterType-int-) | Filtre tipini alır veya ayarlar |
PngFilterType
png dosyası kaydetme sürecinde kullanılır.
|
|  | [getProgressive()](#getProgressive--) | Bu PngSaveOptions'ın ilerleyici olup olmadığını belirten bir değeri alır veya ayarlar. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | Bu PngSaveOptions'ın ilerleyici olup olmadığını belirten bir değeri alır veya ayarlar. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


Varsayılan değerlerle PngSaveOptions oluşturur.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


Bit derinliği.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


Bit derinliği.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


Türünü alır veya ayarlar
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Türünü alır veya ayarlar
PngColorType
.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma seviyesidir
ve 0 depolama modudur.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


0-9 aralığındaki png görüntü sıkıştırma seviyesi, 9 en yüksek sıkıştırma seviyesidir
ve 0 depolama modudur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Filtre tipini alır veya ayarlar
PngFilterType
png dosyası kaydetme sürecinde kullanılır.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Filtre tipini alır veya ayarlar
PngFilterType
png dosyası kaydetme sürecinde kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


Bu PngSaveOptions'ın ilerleyici olup olmadığını belirten bir değeri alır veya ayarlar.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


Bu PngSaveOptions'ın ilerleyici olup olmadığını belirten bir değeri alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

