---
title: "WordProcessingSaveOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Kelime işlem belgeleri için kaydetme seçenekleri."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
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
| [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | WordProcessingSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır. |
| [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır. |
| [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağı ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | İmzalı belgenin dosya formatını alır veya ayarlar. |
| [setFileFormat(int value)](#setFileFormat-int-) | İmzalı belgenin dosya formatını alır veya ayarlar. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kıl |
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
| fileFormat | int | Çıktı dosya türü [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| overwriteExistingFile | boolean | Aynı dosyayla imzalı dosyanın üzerine yazılıp yazılmayacağını belirten bayrak. |

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


WordProcessingSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağı ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileFormat | int | Çıktı dosya türü [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
| overwriteExistingFile | boolean | Aynı dosyayla imzalı dosyanın üzerine yazılıp yazılmayacağını belirten bayrak. |

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

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl

**Returns:**
java.lang.String -
