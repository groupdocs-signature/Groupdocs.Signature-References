---
title: "SymmetricEncryption"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Tek bir anahtar ve parola tuzu ile veri şifrelemesi için standart simetrik algoritmaları uygular."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
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
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | Parametrelerle simetrik şifreleme algoritması oluşturur. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | Varsayılan parola ile simetrik şifreleme algoritması oluşturur. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | Simetrik algoritmanın tipini alır veya ayarlar. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | Simetrik algoritmanın tipini alır veya ayarlar. |
|
|  | [getKey()](#getKey--) | Şifreleme algoritmasının anahtarını alır veya ayarlar. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | Şifreleme algoritmasının anahtarını alır veya ayarlar. |
|
|  | [getSalt()](#getSalt--) | Şifreleme algoritmasının parolasını alır veya ayarlar. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | Şifreleme algoritmasının parolasını alır veya ayarlar. |
|
|  | [encode(String source)](#encode-java.lang.String-) | Sağlanan algoritma tipi, anahtar ve tuz parametrelerine göre dizeyi şifreler. |
|
|  | [decode(String source)](#decode-java.lang.String-) | Sağlanan algoritma tipi, anahtar ve tuz parametrelerine göre dizeyi çözer. |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


Parametrelerle simetrik şifreleme algoritması oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | algorithmType | int | Simetrik algoritma tipini belirtin |
|
|  | key | java.lang.String | Şifreleme anahtarı |
|
|  | tuz | java.lang.String | Şifreleme için parola |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


Varsayılan parola ile simetrik şifreleme algoritması oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | algorithmType | int | Simetrik algoritma tipini belirtin |
|
|  | key | java.lang.String | Şifreleme anahtarı |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


Simetrik algoritmanın tipini alır veya ayarlar.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


Simetrik algoritmanın tipini alır veya ayarlar.


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


Sağlanan algoritma tipi, anahtar ve tuz parametrelerine göre dizeyi şifreler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | kaynak | java.lang.String | Kodlamak için kaynak dize. |
|

**Returns:**
java.lang.String - Şifrelenmiş dizeyi döndürür.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


Sağlanan algoritma tipi, anahtar ve tuz parametrelerine göre dizeyi çözer.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | kaynak | java.lang.String | Çözmek için şifrelenmiş dize. |
|

**Returns:**
java.lang.String - Çözülmüş dizeyi döndürür.

