---
title: "GifSaveOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Görüntü Belgeleri için Gif formatı kaydetme seçenekleri."
type: docs
weight: 15
url: /tr/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

Görüntü Belgeleri için Gif formatı kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | GifSaveOptions nesnesini varsayılan değerlerle oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF arka plan renk indeksini alır veya ayarlar. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF arka plan renk indeksini alır veya ayarlar. |
|
|  | [getColorResolution()](#getColorResolution--) | GIF renk çözünürlüğünü alır veya ayarlar. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | GIF renk çözünürlüğünü alır veya ayarlar. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren değeri alır veya ayarlar. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren değeri alır veya ayarlar. |
|
|  | [hasTrailer()](#hasTrailer--) | GIF'in trailer içerip içermediğini gösteren değeri alır veya ayarlar. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | GIF'in trailer içerip içermediğini gösteren değeri alır veya ayarlar. |
|
|  | [getInterlaced()](#getInterlaced--) | Görüntünün taramalı olması gerekiyorsa doğru. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | Görüntünün taramalı olması gerekiyorsa doğru. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | Palet girişlerinin sıralanıp sıralanmadığını gösteren değeri alır veya ayarlar. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Palet girişlerinin sıralanıp sıralanmadığını gösteren değeri alır veya ayarlar. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF piksel en‑boy oranını alır veya ayarlar. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF piksel en‑boy oranını alır veya ayarlar. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


GifSaveOptions nesnesini varsayılan değerlerle oluşturur.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF arka plan renk indeksini alır veya ayarlar.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF arka plan renk indeksini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF renk çözünürlüğünü alır veya ayarlar.

<br />

*** ** * ** ***

Renk Çözünürlüğü - Orijinal görüntüde mevcut olan birincil renk başına bit sayısı, 1 eksik. Bu değer, grafikte seçilen renklerin alındığı tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti görüntüyü oluşturmak için birincil renk başına 4 bit içeriyordu. Bu değer, tüm paletin her renk kaynağında mevcut olmasa bile orijinal paletin zenginliğini göstermek için ayarlanmalıdır.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF renk çözünürlüğünü alır veya ayarlar.

<br />

*** ** * ** ***

Renk Çözünürlüğü - Orijinal görüntüde mevcut olan birincil renk başına bit sayısı, 1 eksik. Bu değer, grafikte seçilen renklerin alındığı tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti görüntüyü oluşturmak için birincil renk başına 4 bit içeriyordu. Bu değer, tüm paletin her renk kaynağında mevcut olmasa bile orijinal paletin zenginliğini göstermek için ayarlanmalıdır.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Palet düzeltmesinin uygulanıp uygulanmadığını gösteren değeri alır veya ayarlar.

<br />

*** ** * ** ***

Palet düzeltmesi, görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin en uygun paleti oluşturmak için analiz edilmesi anlamına gelir (görüntü Paleti mevcut değilse veya seçeneklerde belirtilmemişse). Analiz süreci biraz zaman alır, ancak çıktı görüntüsü en uygun renk paletine sahip olur ve sonuç görsel olarak daha iyidir.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Palet düzeltmesinin uygulanıp uygulanmadığını gösteren değeri alır veya ayarlar.

<br />

*** ** * ** ***

Palet düzeltmesi, görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin en uygun paleti oluşturmak için analiz edilmesi anlamına gelir (görüntü Paleti mevcut değilse veya seçeneklerde belirtilmemişse). Analiz süreci biraz zaman alır, ancak çıktı görüntüsü en uygun renk paletine sahip olur ve sonuç görsel olarak daha iyidir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF'in trailer içerip içermediğini gösteren değeri alır veya ayarlar.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF'in trailer içerip içermediğini gösteren değeri alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Görüntünün taramalı olması gerekiyorsa doğru.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Görüntünün taramalı olması gerekiyorsa doğru.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Palet girişlerinin sıralanıp sıralanmadığını gösteren değeri alır veya ayarlar.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Palet girişlerinin sıralanıp sıralanmadığını gösteren değeri alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF piksel en‑boy oranını alır veya ayarlar.

<br />

*** ** * ** ***

Piksel En‑Boy Oranı - Orijinal görüntüdeki pikselin en‑boy oranının bir yaklaşık değerini hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en‑boy oranı yaklaşık değeri şu formüle göre hesaplanır: En‑Boy Oranı = (Piksel En‑Boy Oranı + 15) / 64. Piksel En‑Boy Oranı, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, en geniş piksel 4:1'den en uzun piksel 1:4'e kadar 1/64 artışlarla belirtmeye olanak tanır. Değerler: 0 - En‑boy oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF piksel en‑boy oranını alır veya ayarlar.

<br />

*** ** * ** ***

Piksel En‑Boy Oranı - Orijinal görüntüdeki pikselin en‑boy oranının bir yaklaşık değerini hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en‑boy oranı yaklaşık değeri şu formüle göre hesaplanır: En‑Boy Oranı = (Piksel En‑Boy Oranı + 15) / 64. Piksel En‑Boy Oranı, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, en geniş piksel 4:1'den en uzun piksel 1:4'e kadar 1/64 artışlarla belirtmeye olanak tanır. Değerler: 0 - En‑boy oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

