---
title: "LoadOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Bir belgeyi imzalamak için açarken şifre gibi ek seçenekleri belirtmeye olanak tanır."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

İmzalanacak bir belge açılırken ek seçenekleri (örneğin şifre) belirtmeye olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | LoadOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPassword()](#getPassword--) | Korunan bir belgeyi açmak için şifreyi alır veya ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Korunan bir belgeyi açmak için şifreyi alır veya ayarlar. |
| [getLoadExternalResources()](#getLoadExternalResources--) | Harici belge kaynaklarının yüklenip yüklenmeyeceğini belirten seçenekleri alır veya ayarlar. |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | Harici belge kaynaklarının yüklenip yüklenmeyeceğini belirten seçenekleri alır veya ayarlar. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions sınıfının yeni bir örneğini başlatır.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Korunan bir belgeyi açmak için şifreyi alır veya ayarlar. Ayrıca imzalı belgeyi korumalı olarak kaydetmek için de kullanılacaktır.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Korunan bir belgeyi açmak için şifreyi alır veya ayarlar. Ayrıca imzalı belgeyi korumalı olarak kaydetmek için de kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


Harici belge kaynaklarının yüklenip yüklenmeyeceğini belirten seçenekleri alır veya ayarlar. Bu seçenek devre dışı (false) olduğunda, çok sayıda veya büyük harici kaynak bağlantılarına sahip belgeler için yükleme süresini azaltmaya olanak tanır. Varsayılan değer etkin (true) olarak ayarlanmıştır.

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


Harici belge kaynaklarının yüklenip yüklenmeyeceğini belirten seçenekleri alır veya ayarlar. Bu seçenek devre dışı (false) olduğunda, çok sayıda veya büyük harici kaynak bağlantılarına sahip belgeler için yükleme süresini azaltmaya olanak tanır. Varsayılan değer etkin (true) olarak ayarlanmıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

