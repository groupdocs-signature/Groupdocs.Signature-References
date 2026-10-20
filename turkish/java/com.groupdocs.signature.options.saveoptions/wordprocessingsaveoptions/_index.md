---
title: "WordProcessingSaveOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Kelime işlem belgeleri için kaydetme seçenekleri."
type: docs
weight: 15
url: /tr/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

Kelime işlem belgeleri için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | WordProcessingSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağı ile başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | İmzalı belgenin dosya formatını alır veya ayarlar. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | İmzalı belgenin dosya formatını alır veya ayarlar. |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | İmzalı belge için isteğe bağlı OOXML uyumluluk seviyesi. |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | İmzalı belge için isteğe bağlı OOXML uyumluluk seviyesi. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


WordProcessingSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya türü [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | İmzalı dosyanın aynı dosyayla üzerine yazılıp yazılmayacağını belirten bayrak. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağı ile başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya türü [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


İmzalı belge için isteğe bağlı OOXML uyumluluk seviyesi. Ayarlandığında, şunu geçersiz kılar
orijinal belgenin uyumluluğu. Ne zaman
null
(varsayılan), yüklü belgenin
uyumluluğu korunur. Yalnızca OOXML formatları için geçerlidir
(Docx, Docm, Dotx, Dotm, FlatOpc ve FlatOpc varyantları).


Değer, [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance) öğelerinden biridir.


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


İmzalı belge için isteğe bağlı OOXML uyumluluk seviyesi. Ayarlandığında, şunu geçersiz kılar
orijinal belgenin uyumluluğu. Ne zaman
null
(varsayılan), yüklü belgenin
uyumluluğu korunur. Yalnızca OOXML formatları için geçerlidir
(Docx, Docm, Dotx, Dotm, FlatOpc ve FlatOpc varyantları).


Değer, [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance) öğelerinden biridir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl


**Returns:**
java.lang.String -
