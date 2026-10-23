---
title: "java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belgeden imzaları çıkarmak için seçenekleri temsil eder."
type: docs
weight: 17
url: /tr/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
Arama için Belge sayfa numarasını alır veya ayarlar.
```
public abstract class SearchOptions extends OptionsExtensions
```

Belgeden imzaları çıkarmak için seçenekleri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | İmza araması için sayfaları belirtme seçenekleri. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | İmza araması için sayfaları belirtme seçenekleri. |
| [getPagesSetup()](#getPagesSetup--) | Her Belge sayfasında arama yapmak için bayrak. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Her Belge sayfasında arama yapmak için bayrak. |
| [getAllPages()](#getAllPages--) | Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. |
| [getSkipExternal()](#getSkipExternal--) | İmza çıkarımı için sayfa listesini almak üzere sanal yöntem. |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | İmza çıkarımı için sayfa listesini almak üzere sanal yöntem. |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | Arama için Belge sayfa numarasını alır veya ayarlar. Değer isteğe bağlıdır. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Her Belge sayfasında arama yapmak için bayrak. Varsayılan olarak bu değer true olarak ayarlanır.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Her Belge sayfasında arama yapmak için bayrak. Varsayılan olarak bu değer true olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Her Belge sayfasında arama yapmak için bayrak.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Her Belge sayfasında arama yapmak için bayrak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. Varsayılan değer false olup, belirtilen kriterlere uyan tüm imzaların döndürülmesini gösterir.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. Varsayılan değer false olup, belirtilen kriterlere uyan tüm imzaların döndürülmesini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


totalPages

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


totalPages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Arama için Belge sayfa numarasını alır veya ayarlar. Değer isteğe bağlıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| Toplam sayfa sayısı | int | com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Sayfa numaralarının listesi |

**Returns:**
ProcessLog
### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
