---
title: "PdfSaveOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "PDF belgeleri için kaydetme seçenekleri."
type: docs
weight: 11
url: /tr/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF belgeleri için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | PdfSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | PdfSaveOptions sınıfının yeni bir örneğini üzerine yazma bayrağıyla başlatır. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | İmzalı belgenin dosya formatını alır veya ayarlar. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | İmzalı belgenin dosya formatını alır veya ayarlar. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | İzin şifresi (birincil şifre), izin ayarlarını değiştirmek için bir şifre gerektirir. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | İzin şifresi (birincil şifre), izin ayarlarını değiştirmek için bir şifre gerektirir. |
|
|  | [getPermissions()](#getPermissions--) | PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


PdfSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya türü [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


PdfSaveOptions sınıfının yeni bir örneğini üzerine yazma bayrağıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | İmzalı dosyanın aynı dosyayla üzerine yazılıp yazılmayacağını belirten bayrak. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya türü [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|
|  | overwriteExistingFile | boolean | İmzalı dosyanın aynı dosyayla üzerine yazılıp yazılmayacağını belirten bayrak. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


İmzalı belgenin dosya formatını alır veya ayarlar.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


İmzalı belgenin dosya formatını alır veya ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


İzin şifresi (birincil şifre), izin ayarlarını değiştirmek için bir şifre gerektirir.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


İzin şifresi (birincil şifre), izin ayarlarını değiştirmek için bir şifre gerektirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma.


Bu izinleri değiştirmek için,
PermissionsPassword
ayarlanmalıdır.
Değer, [Permissions](../../com.groupdocs.signature.options/permissions) kaynağından bir bayrak kombinasyonudur.
Bir
null
değer, hiçbir açık iznin uygulanmadığı anlamına gelir.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


PDF belge izinleri, örneğin yazdırma, değiştirme ve veri çıkarma.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
