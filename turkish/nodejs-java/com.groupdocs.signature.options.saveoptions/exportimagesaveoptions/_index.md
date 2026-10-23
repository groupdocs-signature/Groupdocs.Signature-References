---
title: "ExportImageSaveOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belgeleri görüntüye dışa aktarmak için kaydetme seçenekleri."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

Belgeleri görüntüye dışa aktarmak için kaydetme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | ExportAsImageSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | ExportAsImageSaveOptions sınıfının yeni bir örneğini belirtilen dosya formatıyla başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | Dışa aktarım için belge sayfa numarasını alır veya ayarlar. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Dışa aktarım için belge sayfa numarasını alır veya ayarlar. |
| [getExportAllPages()](#getExportAllPages--) | Her sayfayı dışa aktarmak için bayrak. |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | Her sayfayı dışa aktarmak için bayrak. |
| [getPagesSetup()](#getPagesSetup--) | İmzalanacak sayfaları belirtmek için seçenekler. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | İmzalanacak sayfaları belirtmek için seçenekler. |
| [getPageColumns()](#getPageColumns--) | Dışa aktarılan görüntüler için sütun sayısını alır veya ayarlar. |
| [setPageColumns(int value)](#setPageColumns-int-) | Dışa aktarılan görüntüler için sütun sayısını alır veya ayarlar. |
| [getBorder()](#getBorder--) | Görüntü kenar ayarlarını alır veya ayarlar. |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | Görüntü kenar ayarlarını alır veya ayarlar. |
| [getTiffMultipage()](#getTiffMultipage--) | Belge sayfalarını Tiff görüntüsünde farklı çerçevelere yerleştir. |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Belge sayfalarını Tiff görüntüsünde farklı çerçevelere yerleştir. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


ExportAsImageSaveOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


ExportAsImageSaveOptions sınıfının yeni bir örneğini belirtilen dosya formatıyla başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileFormat | int | Çıktı görüntü dosya formatı. |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Dışa aktarım için belge sayfa numarasını alır veya ayarlar. Minimum değer 1'dir.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Dışa aktarım için belge sayfa numarasını alır veya ayarlar. Minimum değer 1'dir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


Her sayfayı dışa aktarmak için bayrak.

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


Her sayfayı dışa aktarmak için bayrak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


İmzalanacak sayfaları belirtmek için seçenekler.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


İmzalanacak sayfaları belirtmek için seçenekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


Dışa aktarılan görüntüler için sütun sayısını alır veya ayarlar. Görüntüleri bir satırda yerleştirmeniz gerektiğinde bu özelliği kullanın.

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


Dışa aktarılan görüntüler için sütun sayısını alır veya ayarlar. Görüntüleri bir satırda yerleştirmeniz gerektiğinde bu özelliği kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


Görüntü kenar ayarlarını alır veya ayarlar. Varsayılan olarak bu değer ayarlanmamıştır.

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


Görüntü kenar ayarlarını alır veya ayarlar. Varsayılan olarak bu değer ayarlanmamıştır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Belge sayfalarını Tiff görüntüsünde farklı çerçevelere yerleştir.

**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Belge sayfalarını Tiff görüntüsünde farklı çerçevelere yerleştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
