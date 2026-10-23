---
title: "Dolgu"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Elemanla ilişkili dolgu veya kenar boşluğu bilgilerini temsil eder."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

Elemanla ilişkili dolgu veya kenar boşluğu bilgilerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Padding()](#Padding--) | Dolgu sınıfının yeni bir örneğini sıfır değerleri kullanarak başlatır. |
| [Padding(int all)](#Padding-int-) | Dolgu sınıfının yeni bir örneğini tüm kenarlar için sağlanan dolgu boyutunu kullanarak başlatır. |
| [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | Dolgu sınıfının yeni bir örneğini sağlanan dolgu boyutlarını kullanarak başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Empty](#Empty) | Dolgu içermeyen bir Padding nesnesi sağlar. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAll()](#getAll--) | Tüm kenarlar için dolgu değerini alır veya ayarlar. |
| [setAll(int value)](#setAll-int-) | Tüm kenarlar için dolgu değerini alır veya ayarlar. |
| [getLeft()](#getLeft--) | Sol kenar için dolgu değerini alır veya ayarlar. |
| [setLeft(int value)](#setLeft-int-) | Sol kenar için dolgu değerini alır veya ayarlar. |
| [getRight()](#getRight--) | Sağ kenar için dolgu değerini alır veya ayarlar. |
| [setRight(int value)](#setRight-int-) | Sağ kenar için dolgu değerini alır veya ayarlar. |
| [getTop()](#getTop--) | Üst kenar için dolgu değerini alır veya ayarlar. |
| [setTop(int value)](#setTop-int-) | Üst kenar için dolgu değerini alır veya ayarlar. |
| [getBottom()](#getBottom--) | Alt kenar için dolgu değerini alır veya ayarlar. |
| [setBottom(int value)](#setBottom-int-) | Alt kenar için dolgu değerini alır veya ayarlar. |
| [getHorizontal()](#getHorizontal--) | Sağ ve sol kenarlar için birleşik dolguyu alır. |
| [getVertical()](#getVertical--) | Üst ve alt kenarlar için birleşik dolguyu alır. |
| [deepClone()](#deepClone--) | Bu nesnenin bir kopyasını alır. |
| [toString()](#toString--) | String'e dönüşümü geçersiz kılar. |
### Padding() {#Padding--}
```
public Padding()
```


Dolgu sınıfının yeni bir örneğini sıfır değerleri kullanarak başlatır.

### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


Dolgu sınıfının yeni bir örneğini tüm kenarlar için sağlanan dolgu boyutunu kullanarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tümü | int | Tüm kenarlar için kullanılacak dolgu ölçü birimlerinin sayısı. |

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


Dolgu sınıfının yeni bir örneğini sağlanan dolgu boyutlarını kullanarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sol | int | Sol dolgu boyutu. |
| sağ | int | Sağ dolgu boyutu. |
| üst | int | Üst dolgu boyutu. |
| alt | int | Alt dolgu boyutu. |

### Empty {#Empty}
```
public static final Padding Empty
```


Dolgu içermeyen bir Padding nesnesi sağlar.

### getAll() {#getAll--}
```
public final int getAll()
```


Tüm kenarlar için dolgu değerini alır veya ayarlar. Sol veya üst gibi herhangi bir kısmi kenarın değiştirilmesi bu özelliği 0 yapar;

**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


Tüm kenarlar için dolgu değerini alır veya ayarlar. Sol veya üst gibi herhangi bir kısmi kenarın değiştirilmesi bu özelliği 0 yapar;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Sol kenar için dolgu değerini alır veya ayarlar.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Sol kenar için dolgu değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


Sağ kenar için dolgu değerini alır veya ayarlar.

**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Sağ kenar için dolgu değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Üst kenar için dolgu değerini alır veya ayarlar.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Üst kenar için dolgu değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


Alt kenar için dolgu değerini alır veya ayarlar.

**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Alt kenar için dolgu değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


Sağ ve sol kenarlar için birleşik dolguyu alır.

**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


Üst ve alt kenarlar için birleşik dolguyu alır.

**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Bu nesnenin bir kopyasını alır.

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


String'e dönüşümü geçersiz kılar.

**Returns:**
java.lang.String -
