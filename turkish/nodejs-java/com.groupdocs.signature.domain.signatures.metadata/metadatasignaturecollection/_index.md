---
title: "MetadataSignatureCollection"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Metadata imza nesnelerinin koleksiyonu."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Metadata imza nesnelerinin koleksiyonu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Metadata imzasının koleksiyonunu oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını alır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(String name)](#contains-java.lang.String-) | Belirtilen ada sahip bir Metadata koleksiyonda mevcutsa true döndürür. |
| [indexOf(String name)](#indexOf-java.lang.String-) | Adına göre bir özelliğin dizinini alır. |
| [remove(String name)](#remove-java.lang.String-) | Belirtilen ada sahip bir Metadata İmzasını koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki bir Metadata İmzasını kaldırır. |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | Metadata İmza nesnesini koleksiyona ekle. |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Metadata İmza koleksiyonunu ekle. |
| [deepClone()](#deepClone--) | Metadata İmza Öğeleriyle Metadata İmza Koleksiyonu sınıfını klonla. |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Metadata imzasının koleksiyonunu oluşturur.

### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyondaki öğe sayısını alır.

**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Belirtilen ada sahip bir Metadata koleksiyonda mevcutsa true döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Özelliğin büyük/küçük harf duyarsız adı. |

**Returns:**
boolean - Metadata koleksiyonda mevcutsa true; aksi takdirde false.
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


Adına göre bir özelliğin dizinini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | MetadataSignature'ın büyük/küçük harf duyarsız adı. |

**Returns:**
int - Sıfır tabanlı indeks. Bulunamazsa negatif değer.
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


Belirtilen ada sahip bir Metadata İmzasını koleksiyondan kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String | Metadata İmzasının büyük/küçük harf duyarsız adı. |

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


Belirtilen dizindeki bir Metadata İmzasını kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Sıfır tabanlı indeks. |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


Metadata İmza nesnesini koleksiyona ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Koleksiyona eklenecek metadata imzası. |

--------------------

İsim değeri mevcut koleksiyonda benzersiz değilse bir istisna fırlatır |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Metadata İmza koleksiyonunu ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | Eklenecek imzaların koleksiyonu. |

--------------------

İsim değeri mevcut koleksiyonda benzersiz değilse bir istisna fırlatır |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Metadata İmza Öğeleriyle Metadata İmza Koleksiyonu sınıfını klonla.

**Returns:**
java.lang.Object - Klonlanmış İmza Öğeleriyle kopyalanmış örneği döndürür
