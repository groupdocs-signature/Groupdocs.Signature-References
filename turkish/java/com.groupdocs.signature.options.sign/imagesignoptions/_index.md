---
title: "ImageSignOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Görüntü imza seçeneklerini temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

Görüntü imza seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | ImageSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | ImageSignOptions sınıfının yeni bir örneğini görüntü dosyasıyla başlatır. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | ImageSignOptions sınıfının yeni bir örneğini görüntü akışıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | İmza görüntüsü dosya yolunu alır veya ayarlar. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | İmza görüntüsü dosya yolunu alır veya ayarlar. |
|
|  | [getImageStream()](#getImageStream--) | İmza görüntüsü akışını alır veya ayarlar. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | İmza görüntüsü akışını alır veya ayarlar. |
|
|  | [getLeft()](#getLeft--) | Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
|
|  | [setLeft(int value)](#setLeft-int-) | Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
|
|  | [getTop()](#getTop--) | Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
|
|  | [setTop(int value)](#setTop-int-) | Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
|
|  | [getWidth()](#getWidth--) | Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType bölümüne bakınız).
|
|  | [setHeight(int value)](#setHeight-int-) | Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde |
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType bölümüne bakınız).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre). |
|
|  | [getStretch()](#getStretch--) | Belge sayfasındaki germe modu. |
|
|  | [setStretch(int value)](#setStretch-int-) | Belge sayfasındaki germe modu. |
|
|  | [getRotationAngle()](#getRotationAngle--) | Belge sayfasındaki imzanın döndürme açısı (saat yönünde). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Belge sayfasındaki imzanın döndürme açısı (saat yönünde). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | Belge sayfasındaki imzanın yatay hizalaması. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Belge sayfasındaki imzanın yatay hizalaması. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | Belge sayfasındaki imzanın dikey hizalaması. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Belge sayfasındaki imzanın dikey hizalaması. |
|
|  | [getMargin()](#getMargin--) | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar. |
|
|  | [getTransparency()](#getTransparency--) | İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. |
|
|  | [getShapePosition()](#getShapePosition--) | Şeklin belge düzeninde nerede sunulacağını tanımlar. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | Şeklin belge düzeninde nerede sunulacağını tanımlar. |
|
|  | [getRectangle()](#getRectangle--) | Belgeye görüntünün yerleştirileceği alanın dikdörtgeni. |
|
|  | [getBorder()](#getBorder--) | Kenarlık ayarlarını belirtin. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Kenarlık ayarlarını belirtin. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Base64'ten önceden tanımlı Görüntü ile ImageSignOptions sınıfının yeni bir örneğini oluşturur. |
|
|  | [dispose()](#dispose--) | Dahili kaynakları temizler. |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


ImageSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


ImageSignOptions sınıfının yeni bir örneğini görüntü dosyasıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | Görüntü dosya yolu. |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


ImageSignOptions sınıfının yeni bir örneğini görüntü akışıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | Görüntü akışı. |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


İmza görüntüsü dosya yolunu alır veya ayarlar.
Bu özellik yalnızca ImageStream belirtilmemişse kullanılır.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


İmza görüntüsü dosya yolunu alır veya ayarlar.
Bu özellik yalnızca ImageStream belirtilmemişse kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


İmza görüntüsü akışını alır veya ayarlar.
Bu özellik belirtilirse, her zaman ImageGuid yerine kullanılır.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


İmza görüntüsü akışını alır veya ayarlar.
Bu özellik belirtilirse, her zaman ImageGuid yerine kullanılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
(yatay hizalama belirtilmemişse çalışır).


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Belge sayfasındaki İmzanın sol X konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
(yatay hizalama belirtilmemişse çalışır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
(dikey hizalama belirtilmemişse çalışır).


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Belge sayfasındaki İmzanın üst Y konumu ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType bölümüne bakınız).
(dikey hizalama belirtilmemişse çalışır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde
(piksel, yüzde veya milimetre [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Belge sayfasındaki İmzanın genişliği ölçüm değerlerinde
(piksel, yüzde veya milimetre [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType bölümüne bakınız).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Belge sayfasındaki İmzanın yüksekliği ölçüm değerlerinde
(piksel, yüzde veya milimetre, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType bölümüne bakınız).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


Sol ve Üst özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


Genişlik ve Yükseklik özellikleri için ölçüm türü (piksel, yüzde veya milimetre).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


Belge sayfasındaki germe modu.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


Belge sayfasındaki germe modu.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Belge sayfasındaki imzanın döndürme açısı (saat yönünde).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Belge sayfasındaki imzanın döndürme açısı (saat yönünde).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


Belge sayfasındaki imzanın yatay hizalaması.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


Belge sayfasındaki imzanın yatay hizalaması.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


Belge sayfasındaki imzanın dikey hizalaması.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


Belge sayfasındaki imzanın dikey hizalaması.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar.
(YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır).


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


İmza ile belge kenarları arasındaki boşluğu alır veya ayarlar.
(YALNIZCA yatay veya dikey hizalama belirtilmişse çalışır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Margin için ölçü tipini (piksel, yüzde veya milimetre) alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. Varsayılan değer 0 (opak)dır.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


İmza şeffaflığını (0.0 (opak) ile 1.0 (şeffaf) arasında değer) alır veya ayarlar. Varsayılan değer 0 (opak)dır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


Şeklin belge düzeninde nerede sunulacağını tanımlar.


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


Şeklin belge düzeninde nerede sunulacağını tanımlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Belgeye görüntünün yerleştirileceği alanın dikdörtgeni.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Kenarlık ayarlarını belirtin.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Kenarlık ayarlarını belirtin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Base64'ten önceden tanımlı Görüntü ile ImageSignOptions sınıfının yeni bir örneğini oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | base64Content | java.lang.String | Base64 dize formatındaki görüntü içeriği. |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


Dahili kaynakları temizler.


