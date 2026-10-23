---
title: "Köşeler"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Kare grafik nesnenin köşelerini temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Kare grafik nesnenin köşelerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Corners()](#Corners--) | Sıfır değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır. |
| [Corners(double all)](#Corners-double-) | Tüm köşeler için sağlanan değeri kullanarak Corners sınıfının yeni bir örneğini başlatır. |
| [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Sağlanan değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Empty](#Empty) | Veri içermeyen bir Corners nesnesi sağlar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAll()](#getAll--) | Tüm köşeler için değeri alır veya ayarlar. |
| [setAll(double value)](#setAll-double-) | Tüm köşeler için değeri alır veya ayarlar. |
| [getTopLeft()](#getTopLeft--) | Üst sol köşe değerini alır veya ayarlar. |
| [setTopLeft(double value)](#setTopLeft-double-) | Üst sol köşe değerini alır veya ayarlar. |
| [getTopRight()](#getTopRight--) | Üst sağ köşe değerini alır veya ayarlar. |
| [setTopRight(double value)](#setTopRight-double-) | Üst sağ köşe değerini alır veya ayarlar. |
| [getBottomLeft()](#getBottomLeft--) | Alt sol köşe değerini alır veya ayarlar. |
| [setBottomLeft(double value)](#setBottomLeft-double-) | Alt sol köşe değerini alır veya ayarlar. |
| [getBottomRight()](#getBottomRight--) | Alt sağ köşe değerini alır veya ayarlar. |
| [setBottomRight(double value)](#setBottomRight-double-) | Alt sağ köşe değerini alır veya ayarlar. |
| [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
| [equals(Object obj)](#equals-java.lang.Object-) | Equals metodunu geçersiz kılar |
| [hashCode()](#hashCode--) | Benzersiz hash kodu değerinin elde edilmesini geçersiz kılar |
| [toString()](#toString--) | String'e dönüşümünü geçersiz kılar. |
### Corners() {#Corners--}
```
public Corners()
```


Sıfır değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır.

### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


Tüm köşeler için sağlanan değeri kullanarak Corners sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tümü | double | Tüm köşeler için dolgu olarak kullanılacak değer. |

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Sağlanan değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| topLeft | double | Üst sol köşe değeri. |
| topRight | double | Üst sağ köşe değeri. |
| bottomLeft | double | Alt sol köşe değeri. |
| bottomRight | double | Alt sağ köşe değeri. |

### Empty {#Empty}
```
public static final Corners Empty
```


Veri içermeyen bir Corners nesnesi sağlar.

### getAll() {#getAll--}
```
public final double getAll()
```


Tüm köşeler için değeri alır veya ayarlar. Üst sağ gibi herhangi bir kısmi köşenin değiştirilmesi bu özelliği 0 yapar;

**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Tüm köşeler için değeri alır veya ayarlar. Üst sağ gibi herhangi bir kısmi köşenin değiştirilmesi bu özelliği 0 yapar;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Üst sol köşe değerini alır veya ayarlar.

**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Üst sol köşe değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Üst sağ köşe değerini alır veya ayarlar.

**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Üst sağ köşe değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Alt sol köşe değerini alır veya ayarlar.

**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Alt sol köşe değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Alt sağ köşe değerini alır veya ayarlar.

**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Alt sağ köşe değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Bu nesnenin bir kopyasını alır.

**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Equals metodunu geçersiz kılar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak örnek. |

**Returns:**
boolean - Nesnelerin özellikleri eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Benzersiz hash kodu değerinin elde edilmesini geçersiz kılar

**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


String'e dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
