---
title: "StampSignOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Damga imza seçeneklerini temsil eder."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

Damga imza seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StampSignOptions()](#StampSignOptions--) | StampSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | StampSignOptions sınıfının yeni bir örneğini hizalama seçenekleriyle başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getStampType()](#getStampType--) | Damga tipini alır veya ayarlar. |
| [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | Damga tipini alır veya ayarlar. |
| [getOuterLines()](#getOuterLines--) | Dış Çizgilerin, eşmerkezli daireler olarak render edilen listesi. |
| [getInnerLines()](#getInnerLines--) | İç Çizgilerin, dikdörtgenler kümesi olarak render edilen listesi. |
| [getBackground()](#getBackground--) | Damganın arka planını alır veya ayarlar. |
| [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | Damganın arka planını alır veya ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | İmzanın arka plan rengini alır veya ayarlar. |
| [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | İmzanın arka plan rengini alır veya ayarlar. |
| [getBackgroundBrush()](#getBackgroundBrush--) | İmza arka plan fırçasını alır veya ayarlar. |
| [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | İmza arka plan fırçasını alır veya ayarlar. |
| [getBackgroundColorCropType()](#getBackgroundColorCropType--) | İmzanın arka plan rengi kırpma türünü alır veya ayarlar. |
| [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | İmzanın arka plan rengi kırpma türünü alır veya ayarlar. |
| [getBackgroundImageCropType()](#getBackgroundImageCropType--) | İmzanın arka plan resmi kırpma türünü alır veya ayarlar. |
| [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | İmzanın arka plan resmi kırpma türünü alır veya ayarlar. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kıl |
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


StampSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


StampSignOptions sınıfının yeni bir örneğini hizalama seçenekleriyle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int | Damga İmzasının sol üst kenarının x koordinatı |
| üst | int | Damga İmzasının sol üst kenarının y koordinatı |
| genişlik | int | Damga İmzasının genişliği |
| yükseklik | int | Damga İmzasının yüksekliği |

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


Damga türünü alır veya ayarlar. Varsayılan değer Yuvarlaktır.

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


Damga türünü alır veya ayarlar. Varsayılan değer Yuvarlaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


Dış Çizgilerin, eşmerkezli daireler olarak render edilen listesi.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


İç Çizgilerin, dikdörtgenler kümesi olarak render edilen listesi.

**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


Damganın arka planını alır veya ayarlar.

**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


Damganın arka planını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


İmzanın arka plan rengini alır veya ayarlar.

**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


İmzanın arka plan rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


İmza arka plan fırçasını alır veya ayarlar. Varsayılan değer null'dır.

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


İmza arka plan fırçasını alır veya ayarlar. Varsayılan değer null'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


İmzanın arka plan rengi kırpma türünü alır veya ayarlar.

**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


İmzanın arka plan rengi kırpma türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


İmzanın arka plan resmi kırpma türünü alır veya ayarlar.

**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


İmzanın arka plan resmi kırpma türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl

**Returns:**
java.lang.String -
