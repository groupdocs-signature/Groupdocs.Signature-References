---
title: "PdfSaveOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "PDF belgeleri için kaydetme seçenekleri."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
| [PdfSaveOptions()](#PdfSaveOptions--) | PdfSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır. |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | PdfSaveOptions sınıfının yeni bir örneğini üzerine yazma bayrağı ile başlatır. |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağı ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | İmzalı belgenin dosya formatını alır veya ayarlar. |
| [setFileFormat(int value)](#setFileFormat-int-) | İmzalı belgenin dosya formatını alır veya ayarlar. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
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
| fileFormat | int | Çıktı dosya türü [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


PdfSaveOptions sınıfının yeni bir örneğini üzerine yazma bayrağı ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| overwriteExistingFile | boolean | Aynı dosyayla imzalı dosyanın üzerine yazılıp yazılmayacağını belirten bayrak. |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PdfSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağı ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileFormat | int | Çıktı dosya türü [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
