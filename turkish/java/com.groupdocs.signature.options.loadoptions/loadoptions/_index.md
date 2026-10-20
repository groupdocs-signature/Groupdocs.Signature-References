---
title: "LoadOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Bir belgeyi imzalamak için açarken şifre gibi ek seçenekleri belirtmeye olanak tanır."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature.options.loadoptions/loadoptions/
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
|  | [LoadOptions()](#LoadOptions--) | LoadOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | Belirtilen dosya türüyle LoadOptions sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Korunan bir belgeyi açmak için şifreyi alır veya ayarlar. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Korunan bir belgeyi açmak için şifreyi alır veya ayarlar. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | Belge yüklendiğinde belgenin dışındaki kaynakların atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar. |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | Belge yüklendiğinde belgenin dışındaki kaynakların atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | Yüklenebilecek dış kaynakların adres bölümlerini alır veya ayarlar while |
#getSkipExternalResources().getSkipExternalResources() true ise.
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | Yüklenebilecek dış kaynakların adres bölümlerini alır veya ayarlar while |
#getSkipExternalResources().getSkipExternalResources() true ise.
|
|  | [getPermissions()](#getPermissions--) | PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | Dosyadan ayrıştırılan izinleri kaydetmek için belge yükleme işlemcileri tarafından kullanılan dahili ayarlayıcı. |
|
|  | [getFileType()](#getFileType--) | Belgenin dosya türünü alır. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Belgenin dosya türünü ayarlar, böylece belge içeriğinden algılanmaz. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions sınıfının yeni bir örneğini başlatır.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


Belirtilen dosya türüyle LoadOptions sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | Belgenin dosya türü, #setFileType(FileType).setFileType(FileType) bakınız. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Korunan bir belgeyi açmak için şifreyi alır veya ayarlar.
İmzalı belgeyi korumalı olarak kaydetmek için de kullanılacaktır.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Korunan bir belgeyi açmak için şifreyi alır veya ayarlar.
İmzalı belgeyi korumalı olarak kaydetmek için de kullanılacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


Belge yüklendiğinde belgenin dışındaki kaynakların atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar.
Varsayılan değer true'dır.


Bir belge, dışındaki kaynaklara başvurabilir: kelime işlemde bağlanmış görüntüler ve INCLUDEPICTURE alanları
belgeler, sunum ve elektronik tablolardaki bağlanmış resimler, bir SVG görüntüsünün başvurduğu görüntüler ve stil sayfaları.
Böyle bir kaynağı yüklemek, belgede yazılı adresi talep etmek anlamına gelir. İşleyen bir sunucuda
başkalarının belgelerinden bu, sunucu tarafı istek sahteciliği riski oluşturur ve çevrim dışı kurulumda
istek başarısız olur veya zaman aşımı bekler.


true olduğunda, adresi aşağıdakilerden birini içerenler dışındaki dış kaynaklar yüklenmez
#getWhitelistedResources().getWhitelistedResources(). Atlanan kaynaklar sayfa ön izlemelerinde veya belgeler şu şekilde kaydedildiğinde çizilmez
görüntüler ve resim, barkod ve QR-kod araması onları görmez. Gömülü görüntüler etkilenmez ve
hiperbağlantılar asla izlenmez. Ayar ayrıca arşiv içindeki belgelere de uygulanır.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


Belge yüklendiğinde belgenin dışındaki kaynakların atlanıp atlanmayacağını belirten bayrağı alır veya ayarlar.
Varsayılan değer doğrudur. Bakınız #getSkipExternalResources().getSkipExternalResources().


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


Yüklenebilecek dış kaynakların adres bölümlerini alır veya ayarlar while
#getSkipExternalResources().getSkipExternalResources() doğrudur. Bir adres, onlardan birini içerdiğinde, büyük/küçük harf dikkate alınmadan yüklenir.
Boş değerler yok sayılır. Varsayılan boş bir listedir; null ayarlamak onu temizler.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


Yüklenebilecek dış kaynakların adres bölümlerini alır veya ayarlar while
#getSkipExternalResources().getSkipExternalResources() doğrudur. Bakınız #getWhitelistedResources().getWhitelistedResources().


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma.
Yalnızca PDF belgeleri için. Salt okunur \\u2014 belge yüklenirken otomatik olarak doldurulur.
Değer, [Permissions](../../com.groupdocs.signature.options/permissions) kaynağından bir bayrak kombinasyonudur.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


Dosyadan ayrıştırılan izinleri kaydetmek için belge yükleme işlemcileri tarafından kullanılan dahili ayarlayıcı.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Belgenin dosya tipini alır. Bu [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (varsayılan) olduğunda,
dosya tipi belge içeriğinden algılanır.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Belgenin dosya türünü ayarlar, böylece belge içeriğinden algılanmaz.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

