---
title: "SymmetricEncryption"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Tek bir anahtar ve parola tuzu ile veri şifreleme için standart simetrik algoritmaları uygular."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

Tek anahtar ve parola (tuz) ile veri şifrelemesi için standart simetrik algoritmaları uygular.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Parametrelerle simetrik şifreleme algoritması oluşturur. |
| [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Varsayılan parola ile simetrik şifreleme algoritması oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAlgorithmType()](#getAlgorithmType--) | Simetrik algoritmanın türünü alır veya ayarlar. |
| [setAlgorithmType(int value)](#setAlgorithmType-int-) | Simetrik algoritmanın türünü alır veya ayarlar. |
| [getKey()](#getKey--) | Şifreleme algoritmasının anahtarını alır veya ayarlar. |
| [setKey(String value)](#setKey-java.lang.String-) | Şifreleme algoritmasının anahtarını alır veya ayarlar. |
| [getSalt()](#getSalt--) | Şifreleme algoritmasının parolasını alır veya ayarlar. |
| [setSalt(String value)](#setSalt-java.lang.String-) | Şifreleme algoritmasının parolasını alır veya ayarlar. |
| [encode(String source)](#encode-java.lang.String-) | Sağlanan algoritma türü, anahtar ve tuz parametrelerine göre dizeyi şifreler. |
| [decode(String source)](#decode-java.lang.String-) | Sağlanan algoritma türü, anahtar ve tuz parametrelerine göre dizeyi çözer. |
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Parametrelerle simetrik şifreleme algoritması oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| algorithmType | int | Simetrik algoritma türünü belirtin |
| anahtar | java.lang.String | Şifreleme anahtarı |
| tuz | java.lang.String | Şifreleme için parola |

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Varsayılan parola ile simetrik şifreleme algoritması oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| algorithmType | int | Simetrik algoritma türünü belirtin |
| anahtar | java.lang.String | Şifreleme anahtarı |

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Simetrik algoritmanın türünü alır veya ayarlar.

**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Simetrik algoritmanın türünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


Şifreleme algoritmasının anahtarını alır veya ayarlar.

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Şifreleme algoritmasının anahtarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


Şifreleme algoritmasının parolasını alır veya ayarlar.

**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


Şifreleme algoritmasının parolasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


Sağlanan algoritma türü, anahtar ve tuz parametrelerine göre dizeyi şifreler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | java.lang.String | Kodlanacak kaynak dize. |

**Returns:**
java.lang.String - Şifrelenmiş dizeyi döndürür.
### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Sağlanan algoritma türü, anahtar ve tuz parametrelerine göre dizeyi çözer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | java.lang.String | Çözülecek şifrelenmiş dize. |

**Returns:**
java.lang.String - Çözülmüş dizeyi döndürür.
