---
title: "Kenarlık"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Kenarlık çizgi özelliklerini tutmak için örnek."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

Kenarlık çizgi özelliklerini tutmak için örnek.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Border()](#Border--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDashStyle()](#getDashStyle--) | İmza kenarlık stilini alır veya ayarlar. |
| [setDashStyle(int value)](#setDashStyle-int-) | İmza kenarlık stilini alır veya ayarlar. |
| [getTransparency()](#getTransparency--) | İmza kenarlık şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). |
| [setTransparency(double value)](#setTransparency-double-) | İmza kenarlık şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). |
| [getWeight()](#getWeight--) | İmza kenarlığının kalınlığını alır veya ayarlar. |
| [setWeight(double value)](#setWeight-double-) | İmza kenarlığının kalınlığını alır veya ayarlar. |
| [getColor()](#getColor--) | İmzanın kenarlık rengini alır veya ayarlar. |
| [setColor(Color value)](#setColor-java.awt.Color-) | İmzanın kenarlık rengini alır veya ayarlar. |
| [setColor(String value)](#setColor-java.lang.String-) | İmzanın kenarlık rengini alır veya ayarlar. |
| [getVisible()](#getVisible--) | Kenarlık görünürlüğünü alır veya ayarlar. |
| [setVisible(boolean value)](#setVisible-boolean-) |  |
| [deepClone()](#deepClone--) | IClonable arayüzünü uygula |
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


İmza kenarlık stilini alır veya ayarlar.

**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


İmza kenarlık stilini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


İmza kenarlık şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


İmza kenarlık şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


İmza kenarlığının kalınlığını alır veya ayarlar.

**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


İmza kenarlığının kalınlığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


İmzanın kenarlık rengini alır veya ayarlar.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


İmzanın kenarlık rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


İmzanın kenarlık rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Kenarlık görünürlüğünü alır veya ayarlar.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


IClonable arayüzünü uygula

**Returns:**
java.lang.Object - Aynı özelliklere sahip yeni oluşturulan Border örneği
