---
title: "MetadataSignature"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Metadata imza özelliklerini içerir."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

Metadata imza özelliklerini içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getName()](#getName--) | Benzersiz meta veri adını belirtir. |
| [setName(String value)](#setName-java.lang.String-) | Benzersiz meta veri adını belirtir. |
| [getValue()](#getValue--) | Meta veri nesnesini belirtir. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Meta veri nesnesini belirtir. |
| [getType()](#getType--) | Meta veri değer tipini belirtir. |
| [setType(int value)](#setType-int-) | Meta veri değer tipini belirtir. |
| [getDataEncryption()](#getDataEncryption--) | İmza Değeri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | İmza Değeri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar. |
| [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | Serileştirme sonrası Metadata Signature Value'dan nesne elde eder. |
| [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Serileştirme sonrası Metadata Signature Text'ten nesne elde eder. |
| [equals(Object signature)](#equals-java.lang.Object-) | İmza özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
| [toBoolean()](#toBoolean--) | Boolean'a dönüştürür. |
| [toInteger()](#toInteger--) | Tam sayıya dönüştürür. |
| [toDouble()](#toDouble--) | Double'a dönüştürür. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Double'a dönüştürür. |
| [toSingle()](#toSingle--) | Float'a dönüştürür. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | Float'a dönüştürür. |
| [toDateTime()](#toDateTime--) | DateTime'a dönüştürür. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | DateTime'a dönüştürür. |
| [toString()](#toString--) | ToString() yöntemiyle geçersiz kılma yaparak String'e dönüştürür |
| [toString(String format)](#toString-java.lang.String-) | Belirtilen formatla String'e dönüştürür |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | Belirtilen formatla String'e dönüştürür |
| [deepClone()](#deepClone--) | Metadata Signature örneğini kopyalar. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | Verilen değerle Metadata Signature örneğini kopyalar. |
### getName() {#getName--}
```
public final String getName()
```


Benzersiz meta veri adını belirtir.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Benzersiz meta veri adını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Meta veri nesnesini belirtir.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Meta veri nesnesini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


Meta veri değer tipini belirtir.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Meta veri değer tipini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


İmza Değeri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


İmza Değeri özelliklerini kodlamak ve çözmek için [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) arayüzünün uygulamasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


Serileştirme sonrası Metadata Signature Value'dan nesne elde eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - T nesnesinin örneği

T : Metadata değerinden ayrıştırılacak nesnenin türü
### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


Serileştirme sonrası Metadata Signature Text'ten nesne elde eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Özel veri şifreleme uygulamasını ayarla |

T : Metadata Değerinden ayrıştırılacak nesnenin türü |

**Returns:**
T -
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
int - İmza hash kodu
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


Boolean'a dönüştürür.

**Returns:**
boolean - Metadata imza değerini boolean olarak döndürür.

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır.
### toInteger() {#toInteger--}
```
public int toInteger()
```


Tam sayıya dönüştürür.

**Returns:**
int - Metadata İmza değerini tam sayı olarak döndürür.

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır.
### toDouble() {#toDouble--}
```
public double toDouble()
```


Double'a dönüştürür.

**Returns:**
double - Metadata İmza değerini Double olarak döndürür.

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer metin tabanlıysa, varsayılan kültür özelliği bilgisi SignatureSettings özelliklerinden SignatureSettings.DefaultCulture kullanılır.
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Double'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sağlayıcı | java.util.Locale | Veri dönüşüm işlemlerinde kullanılacak veri sağlayıcıyı biçimlendir. |

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır |

**Returns:**
double - Metadata İmza değerini Double olarak döndürür.
### toSingle() {#toSingle--}
```
public float toSingle()
```


Float'a dönüştürür.

**Returns:**
float - Metadata İmza değerini float olarak döndürür.

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer metin tabanlıysa, varsayılan kültür özelliği bilgisi SignatureSettings özelliklerinden SignatureSettings.DefaultCulture () kullanılır.
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


Float'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sağlayıcı | java.util.Locale | Veri dönüşüm işlemlerinde kullanılacak veri sağlayıcıyı biçimlendir. |

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır |

**Returns:**
float - Metadata İmza değerini float olarak döndürür.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


DateTime'a dönüştürür.

**Returns:**
java.util.Date - Metadata İmza değerini DateTime olarak döndürür.

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer metin tabanlıysa, varsayılan kültür özelliği bilgisi SignatureSettings özelliklerinden SignatureSettings.DefaultCulture kullanılır.
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


DateTime'a dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | sağlayıcı | java.util.Locale | Veri dönüşüm işlemlerinde kullanılacak veri sağlayıcıyı biçimlendir. |

--------------------

Metadata değeri dönüştürülemezse bir istisna fırlatır |

**Returns:**
java.util.Date - Metadata İmza değerini DateTime olarak döndürür.
### toString() {#toString--}
```
public String toString()
```


ToString() yöntemiyle geçersiz kılma yaparak String'e dönüştürür

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.

--------------------

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Başka bir veri tipi için varsayılan veri biçim sağlayıcısı kullanılacaktır.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


Belirtilen formatla String'e dönüştürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | biçim | java.lang.String | Veri biçim dizesi. |

--------------------

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Varsayılan kültür özelliği bilgisi SignatureSettings özelliklerinden SignatureSettings.DefaultCulture kullanılacaktır |

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


Belirtilen formatla String'e dönüştürür

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| biçim | java.lang.String | Veri biçim dizesi. |
|  | sağlayıcı | java.util.Locale | Veri dönüşüm işlemlerinde kullanılacak veri sağlayıcıyı biçimlendir. |

--------------------

Bir boolean özelliği "True" veya "False" değerine dönüştürür. |

**Returns:**
java.lang.String - Metadata İmza değerini String olarak döndürür.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata Signature örneğini kopyalar.

**Returns:**
java.lang.Object - Kopyalanmış Metadata Signature örneğini döndürür
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Verilen değerle Metadata Signature örneğini kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object | Yeni kopyalanmış nesne için değer. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.
