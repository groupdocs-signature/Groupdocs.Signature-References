---
title: "SpreadsheetSaveOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Elektronik tablo belgeleri için kaydetme seçenekleri."
type: docs
weight: 14
url: /tr/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

Elektronik tablo belgeleri için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | SpreadsheetSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | SpreadsheetSaveOptions sınıfının yeni bir örneğini önceden tanımlı çıktı dosya formatıyla başlatır. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | SpreadsheetSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


SpreadsheetSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


SpreadsheetSaveOptions sınıfının yeni bir örneğini önceden tanımlı çıktı dosya formatıyla başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya formatını belirtir. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


SpreadsheetSaveOptions sınıfının yeni bir örneğini belirtilen çıktı türü ve üzerine yazma bayrağı ile başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileFormat | int | Çıktı dosya formatını belirtir. |
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
