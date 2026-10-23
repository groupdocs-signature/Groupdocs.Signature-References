---
title: "BaseSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "İmzalar için temel sınıfı tanımlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

İmzalar için temel sınıfı tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignatureType()](#getSignatureType--) | İmzanın tipini belirtir. |
| [getPageNumber()](#getPageNumber--) | İmzanın bulunduğu sayfayı belirtir. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | İmzanın bulunduğu sayfayı belirtir. |
| [getSignatureId()](#getSignatureId--) | Güncelleme veya Silme yöntemleriyle belgede imzayı değiştirmek için benzersiz imza tanımlayıcısı. |
| [isSignature()](#isSignature--) | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu göstermek için bayrağı al veya ayarla. |
| [setSignature(boolean value)](#setSignature-boolean-) | Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu göstermek için bayrağı al veya ayarla. |
| [getDeleted()](#getDeleted--) | Bu imzanın belgeden silinip silinmediğini göstermek için bayrağı al veya ayarla. |
| [getCreatedOn()](#getCreatedOn--) | İmza oluşturma tarihini al veya ayarla. |
| [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | İmza oluşturma tarihini al veya ayarla. |
| [getModifiedOn()](#getModifiedOn--) | İmza değiştirme tarihini al veya ayarla. |
| [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | İmza değiştirme tarihini al veya ayarla. |
| [getTop()](#getTop--) | İmzanın üst konumunu belirtir. |
| [setTop(int value)](#setTop-int-) | İmzanın üst konumunu belirtir. |
| [getLeft()](#getLeft--) | İmzanın sol konumunu belirtir. |
| [setLeft(int value)](#setLeft-int-) | İmzanın sol konumunu belirtir. |
| [getWidth()](#getWidth--) | İmzanın genişliğini belirtir. |
| [setWidth(int value)](#setWidth-int-) | İmzanın genişliğini belirtir. |
| [getHeight()](#getHeight--) | İmzanın yüksekliğini belirtir. |
| [setHeight(int value)](#setHeight-int-) | İmzanın yüksekliğini belirtir. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
| [toString()](#toString--) |  |
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


İmzanın tipini belirtir. Dijital imzalar bu özelliğe sahip olacaktır.

**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


İmzanın bulunduğu sayfayı belirtir.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


İmzanın bulunduğu sayfayı belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Güncelleme veya Silme yöntemleriyle belgede imzayı değiştirmek için benzersiz imza tanımlayıcısı. Bu özellik, Sign veya Search yöntemi çağrıldıktan sonra otomatik olarak ayarlanır. Bu özellik daha önce kaydedildiyse, imzayı manipüle etmek için elle ayarlanabilir.

**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu göstermek için bayrağı al veya ayarla. Bu özellik, öğeyi imza (true) veya belge öğesi (false) olarak ayarlamak için Güncelleme yöntemiyle kullanılır.

**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Bu bileşenin İmza mı yoksa belge içeriği mi olduğunu göstermek için bayrağı al veya ayarla. Bu özellik, öğeyi imza (true) veya belge öğesi (false) olarak ayarlamak için Güncelleme yöntemiyle kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Bu imzanın belgeden silinip silinmediğini göstermek için bayrağı al veya ayarla. Bu özellik yalnızca silinen imzaların listesini tutmak için belge geçmişi günlük kayıtlarında kullanılır.

**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


İmza oluşturma tarihini al veya ayarla.

**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


İmza oluşturma tarihini al veya ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


İmza değiştirme tarihini al veya ayarla.

**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


İmza değiştirme tarihini al veya ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


İmzanın üst konumunu belirtir.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


İmzanın üst konumunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


İmzanın sol konumunu belirtir.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


İmzanın sol konumunu belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


İmzanın genişliğini belirtir.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


İmzanın genişliğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


İmzanın yüksekliğini belirtir.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


İmzanın yüksekliğini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
