---
title: "SearchOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belgeden imzaları çıkarmak için seçenekleri temsil eder."
type: docs
weight: 17
url: /tr/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

Belgeden imzaları çıkarmak için seçenekleri temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Arama için Document sayfa numarasını alır veya ayarlar. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Arama için Document sayfa numarasını alır veya ayarlar. |
|
|  | [getPagesSetup()](#getPagesSetup--) | Signature araması için sayfaları belirtme seçenekleri. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Signature araması için sayfaları belirtme seçenekleri. |
|
|  | [getAllPages()](#getAllPages--) | Her Document sayfasında arama yapmak için bayrak. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | Her Document sayfasında arama yapmak için bayrak. |
|
|  | [getSkipExternal()](#getSkipExternal--) | Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | Signature çıkarımı için sayfa listesini almak üzere sanal yöntem. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Arama için Document sayfa numarasını alır veya ayarlar.
Değer isteğe bağlıdır.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Arama için Document sayfa numarasını alır veya ayarlar.
Değer isteğe bağlıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


Signature araması için sayfaları belirtme seçenekleri.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


Signature araması için sayfaları belirtme seçenekleri.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Her Document sayfasında arama yapmak için bayrak. Varsayılan olarak bu değer true olarak ayarlanır.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Her Document sayfasında arama yapmak için bayrak. Varsayılan olarak bu değer true olarak ayarlanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. Varsayılan değer false'tur; bu, belirtilen kriterlere uyan tüm imzaların döndürüleceği anlamına gelir.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


Yalnızca IsSignature olarak işaretlenmiş imzaları döndürmek için bayrak. Varsayılan değer false'tur; bu, belirtilen kriterlere uyan tüm imzaların döndürüleceği anlamına gelir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


Signature çıkarımı için sayfa listesini almak üzere sanal yöntem.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | totalPages | int | Sayfaların toplam sayısı |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Sayfa numaralarının listesi

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kıl.


**Returns:**
java.lang.String -
