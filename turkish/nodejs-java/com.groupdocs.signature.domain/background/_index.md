---
title: "Arka plan"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Arka plan görünümünü temsil eder"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

Arka plan görünümünü temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Background()](#Background--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | İmzanın arka plan rengini alır veya ayarlar. |
| [setColor(Color value)](#setColor-java.awt.Color-) | İmzanın arka plan rengini alır veya ayarlar. |
| [setColor(String value)](#setColor-java.lang.String-) | İmzanın arka plan rengini alır veya ayarlar. |
| [getTransparency()](#getTransparency--) | Arka plan şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). |
| [setTransparency(double value)](#setTransparency-double-) | Arka plan şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında). |
| [getBrush()](#getBrush--) | Arka plan fırçasını alır veya ayarlar. |
| [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | Arka plan fırçasını alır veya ayarlar. |
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


İmzanın arka plan rengini alır veya ayarlar.

**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


İmzanın arka plan rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


İmzanın arka plan rengini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Arka plan şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında).

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Arka plan şeffaflığını alır veya ayarlar (değer 0.0 (opak) ile 1.0 (şeffaf) arasında).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


Arka plan fırçasını alır veya ayarlar. Varsayılan değer null'dur. Bu özellik, Brush nesnelerinin uygulamalarının örneklerini bekler. Farklı Brush sınıflarına bakın

**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


Arka plan fırçasını alır veya ayarlar. Varsayılan değer null'dur. Bu özellik, Brush nesnelerinin uygulamalarının örneklerini bekler. Farklı Brush sınıflarına bakın

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

