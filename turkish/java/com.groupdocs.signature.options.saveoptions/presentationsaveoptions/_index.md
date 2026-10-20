---
title: "PresentationSaveOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Sunum belgeleri için kaydetme seçenekleri."
type: docs
weight: 12
url: /tr/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

Sunum belgeleri için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | PresentationSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | PresentationSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | PresentationSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağıyla başlatır. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | PresentationSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağıyla başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | İmzalı belgenin dosya formatını alır veya ayarlar. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | İmzalı belgenin dosya formatını alır veya ayarlar. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


PresentationSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


PresentationSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya türü [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


PresentationSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | İmzalı dosyanın aynı dosyayla üzerine yazılıp yazılmayacağını belirten bayrak. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PresentationSaveOptions sınıfının yeni bir örneğini belirtilen çıktı dosya formatı ve üzerine yazma bayrağıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya türü [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
