---
title: "Köşeler"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Kare grafik nesnesinin köşelerini temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

Kare grafik nesnesinin köşelerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Corners()](#Corners--) | Sıfır değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır. |
|
|  | [Corners(double all)](#Corners-double-) | Tüm köşeler için sağlanan değeri kullanarak Corners sınıfının yeni bir örneğini başlatır. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | Sağlanan değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Empty](#Empty) | Veri içermeyen bir Corners nesnesi sağlar. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm köşeler için değeri alır veya ayarlar. |
|
|  | [setAll(double value)](#setAll-double-) | Tüm köşeler için değeri alır veya ayarlar. |
|
|  | [getTopLeft()](#getTopLeft--) | Sol üst köşe değerini alır veya ayarlar. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | Sol üst köşe değerini alır veya ayarlar. |
|
|  | [getTopRight()](#getTopRight--) | Sağ üst köşe değerini alır veya ayarlar. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | Sağ üst köşe değerini alır veya ayarlar. |
|
|  | [getBottomLeft()](#getBottomLeft--) | Sol alt köşe değerini alır veya ayarlar. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | Sol alt köşe değerini alır veya ayarlar. |
|
|  | [getBottomRight()](#getBottomRight--) | Sağ alt köşe değerini alır veya ayarlar. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | Sağ alt köşe değerini alır veya ayarlar. |
|
|  | [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Equals metodunu geçersiz kılar. |
|
|  | [hashCode()](#hashCode--) | Benzersiz hash kodu değerini elde etmeyi geçersiz kılar. |
|
|  | [toString()](#toString--) | Stringe dönüşümü geçersiz kılar. |
|
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
|  | tümü | double | Tüm köşeler için dolgu olarak kullanılacak değer. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


Sağlanan değerleri kullanarak Corners sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | topLeft | double | Sol üst köşe değeri. |
|
|  | topRight | double | Sağ üst köşe değeri. |
|
|  | bottomLeft | double | Sol alt köşe değeri. |
|
|  | bottomRight | double | Sağ alt köşe değeri. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


Veri içermeyen bir Corners nesnesi sağlar.


### getAll() {#getAll--}
```
public final double getAll()
```


Tüm köşeler için değeri alır veya ayarlar.
Sağ üst gibi herhangi bir kısmi köşenin değiştirilmesi bu özelliği 0'a eşit yapar;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


Tüm köşeler için değeri alır veya ayarlar.
Sağ üst gibi herhangi bir kısmi köşenin değiştirilmesi bu özelliği 0'a eşit yapar;


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


Sol üst köşe değerini alır veya ayarlar.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


Sol üst köşe değerini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


Sağ üst köşe değerini alır veya ayarlar.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


Sağ üst köşe değerini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


Sol alt köşe değerini alır veya ayarlar.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


Sol alt köşe değerini alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


Sağ alt köşe değerini alır veya ayarlar.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


Sağ alt köşe değerini alır veya ayarlar.


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


Equals metodunu geçersiz kılar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Karşılaştırılacak örnek. |
|

**Returns:**
boolean - Nesnelerin özellikleri eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Benzersiz hash kodu değerini elde etmeyi geçersiz kılar.


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


Stringe dönüşümü geçersiz kılar.


**Returns:**
java.lang.String -
