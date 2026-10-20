---
title: "ImageMetadataSignature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Görüntü Meta Verisi imza özelliklerini içerir."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

Görüntü Meta Verisi imza özelliklerini içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Id ve değerle Image Metadata Signature oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getId()](#getId--) | Image Metadata imzasının tanımlayıcısı. |
|
|  | [setId(int value)](#setId-int-) | Image Metadata imzasının tanımlayıcısı. |
|
|  | [getSize()](#getSize--) | Metadata değerinin boyutunu almak için yalnızca okunabilir değer. |
|
|  | [setSize(int value)](#setSize-int-) | Metadata değerinin boyutunu almak için yalnızca okunabilir değer. |
|
|  | [getDescription()](#getDescription--) | Standart Image Metadata imzası için açıklamayı almak üzere yalnızca okunabilir değer. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar |
|
|  | [hashCode()](#hashCode--) | GetHashCode yöntemini geçersiz kılar |
|
|  | [deepClone()](#deepClone--) | Metadata İmza örneğini kopyalar. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Image Metadata Signature örneğini kopyalar. |
|
|  | [toBoolean()](#toBoolean--) | Boolean'a dönüştürür. |
|
|  | [toInteger()](#toInteger--) | Tam sayıya dönüştürür. |
|
|  | [toLong()](#toLong--) | long'a dönüştürür. |
|
|  | [toSingle()](#toSingle--) | Float'a dönüştürür. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Float'a dönüştürür. |
|
|  | [toDouble()](#toDouble--) | Double'a dönüştürür. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Double'a dönüştürür. |
|
|  | [toDecimal()](#toDecimal--) | Decimal'a dönüştürür. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Decimal'a dönüştürür. |
|
|  | [toDateTime()](#toDateTime--) | DateTime'a dönüştürür. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | DateTime'a dönüştürür. |
|
|  | [toString()](#toString--) | ToString() yöntemiyle geçersiz kılınmış String'e dönüştürür. |
|
|  | [toString(String format)](#toString-java.lang.String-) | Belirtilen formatla String'e dönüştürür. |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Belirtilen formatla String'e dönüştürür. |
|
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Id ve değerle Image Metadata Signature oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | id | int | Image Metadata Signature adının benzersiz tanımlayıcısı. Olası id değerleri için Exif etiketleri spesifikasyonlarına bakınız. |
|
|  | değer | java.lang.Object | Metadata değeri |
|

### getId() {#getId--}
```
public final int getId()
```


Image Metadata imzasının tanımlayıcısı.
Bakın [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) sınıfına, önceden tanımlı Id değerine sahip standart Signature'ı içerir.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Image Metadata imzasının tanımlayıcısı.
Bakın [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) sınıfına, önceden tanımlı Id değerine sahip standart Signature'ı içerir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Metadata değerinin boyutunu almak için yalnızca okunabilir değer.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Metadata değerinin boyutunu almak için yalnızca okunabilir değer.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Standart Image Metadata imzası için açıklamayı almak üzere yalnızca okunabilir değer.


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imza | java.lang.Object | Karşılaştırılacak imza nesnesi. |
|

**Returns:**
boolean - Geçilen imza nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode yöntemini geçersiz kılar


**Returns:**
int - İmza karma kodu

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata İmza örneğini kopyalar.


**Returns:**
java.lang.Object - Kopyalanmış Metadata İmza örneğini döndürür

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Verilen değerle Image Metadata Signature örneğini kopyalar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.Object | Yeni kopyalanmış nesne için değer. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Boolean'a dönüştürür.


**Returns:**
boolean - Metadata imza değerini boolean olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


Tam sayıya dönüştürür.


**Returns:**
int - Metadata Signature değerini tam sayı olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


long'a dönüştürür.


**Returns:**
long - Metadata Signature değerini long olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


Float'a dönüştürür.


**Returns:**
float - Image Metadata Signature değerini float olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer string tabanlıysa, SignatureSettings özelliklerinden SignatureSettings.DefaultCulture varsayılan kültür özelliği kullanılacaktır.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


Float'a dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | provider | java.util.Locale | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcı. |

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />

|

**Returns:**
float - Metadata İmza değerini float olarak döndürür.

### toDouble() {#toDouble--}
```
public double toDouble()
```


Double'a dönüştürür.


**Returns:**
double - Image Metadata Signature değerini Double olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer string tabanlıysa, SignatureSettings özelliklerinden SignatureSettings.DefaultCulture varsayılan kültür özelliği kullanılacaktır.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Double'a dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | provider | java.util.Locale | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcı. |

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />

|

**Returns:**
double - Metadata Signature değerini Double olarak döndürür.

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Decimal'a dönüştürür.


**Returns:**
java.math.BigDecimal - Image Metadata Signature değerini Decimal olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer string tabanlıysa, SignatureSettings özelliklerinden SignatureSettings.DefaultCulture varsayılan kültür özelliği kullanılacaktır.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Decimal'a dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | provider | java.util.Locale | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcı. |

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />

|

**Returns:**
java.math.BigDecimal - Metadata Signature değerini Decimal olarak döndürür.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


DateTime'a dönüştürür.


**Returns:**
java.util.Date - Metadata İmza değerini DateTime olarak döndürür.

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer string tabanlıysa, SignatureSettings özelliklerinden SignatureSettings.DefaultCulture varsayılan kültür özelliği kullanılacaktır.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


DateTime'a dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | provider | java.util.Locale | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcı. |

<br />

*** ** * ** ***

Metadata değeri dönüştürülemezse bir istisna fırlatır.

<br />

|

**Returns:**
java.util.Date - Metadata İmza değerini DateTime olarak döndürür.

### toString() {#toString--}
```
public String toString()
```


ToString() yöntemiyle geçersiz kılınmış String'e dönüştürür.


**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Belirtilen formatla String'e dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | biçim | java.lang.String | Veri formatı dizesi. |

<br />

*** ** * ** ***

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Varsayılan kültür özelliği bilgisi SignatureSettings özelliklerinden SignatureSettings.DefaultCulture kullanılarak sağlanacaktır.

<br />

|

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Belirtilen formatla String'e dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | biçim | java.lang.String | Veri formatı dizesi. |
|
|  | provider | java.util.Locale | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcı. |

<br />

*** ** * ** ***

Bir boolean özelliği "True" veya "False" değerine dönüştürür.

<br />

|

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

