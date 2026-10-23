---
title: "SaveOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Bir belgeyi imzalamak için kaydederken şifre gibi ek seçenekleri belirtmeye izin verir."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

Bir belgeyi imzalamak için kaydederken ek seçenekleri (örneğin şifre) belirtmeye olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | SaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | SaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | Mevcut dosyanın yeni çıktı dosyasıyla üzerine yazılıp yazılmayacağını alır veya ayarlar. |
| [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | Mevcut dosyanın yeni çıktı dosyasıyla üzerine yazılıp yazılmayacağını alır veya ayarlar. |
| [getPassword()](#getPassword--) | İmzalı belgeyi şifre korumasıyla kaydetmek için şifreyi alır veya ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | İmzalı belgeyi şifre korumasıyla kaydetmek için şifreyi alır veya ayarlar. |
| [getUseOriginalPassword()](#getUseOriginalPassword--) | İmzalı belgeyi korumalı olarak kaydetmek için LoadOptions'tan şifre kullanılıp kullanılmayacağını alır veya ayarlar. |
| [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | İmzalı belgeyi korumalı olarak kaydetmek için LoadOptions'tan şifre kullanılıp kullanılmayacağını alır veya ayarlar. |
| [getAddMissingExtenstion()](#getAddMissingExtenstion--) | Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklemek için bayrağı alır veya ayarlar. Varsayılan değer false'tur. |
| [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklemek için bayrağı alır veya ayarlar. Varsayılan değer false'tur. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


SaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


SaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| overwriteExistingFile | boolean | Aynı dosyayla imzalı dosyanın üzerine yazılıp yazılmayacağını belirten bayrak. |

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


Mevcut dosyanın yeni çıktı dosyasıyla üzerine yazılıp yazılmayacağını alır veya ayarlar. Aksi takdirde yeni dosya, sayı ekine sahip olarak oluşturulur.

**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


Mevcut dosyanın yeni çıktı dosyasıyla üzerine yazılıp yazılmayacağını alır veya ayarlar. Aksi takdirde yeni dosya, sayı ekine sahip olarak oluşturulur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


İmzalı belgeyi şifre korumasıyla kaydetmek için şifreyi alır veya ayarlar. Bu özellik Görüntü belgeleri için desteklenmez.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


İmzalı belgeyi şifre korumasıyla kaydetmek için şifreyi alır veya ayarlar. Bu özellik Görüntü belgeleri için desteklenmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


İmzalı belgeyi korumalı olarak kaydetmek için LoadOptions'tan şifre kullanılıp kullanılmayacağını alır veya ayarlar. Varsayılan değer true'tır. Bu özellik Görüntü belgeleri için desteklenmez.

**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


İmzalı belgeyi korumalı olarak kaydetmek için LoadOptions'tan şifre kullanılıp kullanılmayacağını alır veya ayarlar. Varsayılan değer true'tır. Bu özellik Görüntü belgeleri için desteklenmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklemek için bayrağı alır veya ayarlar. Varsayılan değer false'tur.

**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


Çıktı dosya yolunda uzantı eksik olduğunda otomatik olarak eklemek için bayrağı alır veya ayarlar. Varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

