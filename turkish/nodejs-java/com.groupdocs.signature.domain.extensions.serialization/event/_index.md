---
title: "Event"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Standart QR-Kod Etkinlik detaylarını temsil eder."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/event/
---
**Inheritance:**
java.lang.Object
```
public final class Event
```

Standart QR-Kod Etkinlik detaylarını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Event()](#Event--) | Varsayılan değerlerle Event örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTitle()](#getTitle--) | Etkinlik başlığını alır veya ayarlar. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Etkinlik başlığını alır veya ayarlar. |
| [getDescription()](#getDescription--) | Açıklamayı alır veya ayarlar. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Açıklamayı alır veya ayarlar. |
| [getLocation()](#getLocation--) | Etkinlik konumunu alır veya ayarlar. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Etkinlik konumunu alır veya ayarlar. |
| [getStartDate()](#getStartDate--) | Etkinlik başlangıç tarih ve saatini alır veya ayarlar. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Etkinlik başlangıç tarih ve saatini alır veya ayarlar. |
| [getEndDate()](#getEndDate--) | Etkinliğin bitiş tarih ve saatini alır veya ayarlar. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Etkinliğin bitiş tarih ve saatini alır veya ayarlar. |
| [equals(Object source)](#equals-java.lang.Object-) | Event özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
### Event() {#Event--}
```
public Event()
```


Varsayılan değerlerle Event örneği oluşturur.

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Etkinlik başlığını alır veya ayarlar.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Etkinlik başlığını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Açıklamayı alır veya ayarlar.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Açıklamayı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Etkinlik konumunu alır veya ayarlar.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Etkinlik konumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Etkinlik başlangıç tarih ve saatini alır veya ayarlar.

**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Etkinlik başlangıç tarih ve saatini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Etkinliğin bitiş tarih ve saatini alır veya ayarlar.

**Returns:**
java.util.Date
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Etkinliğin bitiş tarih ve saatini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Event özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | java.lang.Object | Karşılaştırılacak Event nesnesi. |

**Returns:**
boolean - Geçilen Event nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - Event karma kodu
