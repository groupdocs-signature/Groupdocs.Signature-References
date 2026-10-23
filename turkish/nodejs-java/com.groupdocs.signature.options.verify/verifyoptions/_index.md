---
title: "VerifyOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belgeyi doğrulamak için seçenekleri tutar."
type: docs
weight: 15
url: /tr/nodejs-java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

Belgeyi doğrulamak için seçenekleri tutar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isValid()](#isValid--) | Geçerli özellik bayrağı. |
| [setValid(boolean value)](#setValid-boolean-) | Geçerli özellik bayrağı. |
| [getPageNumber()](#getPageNumber--) | Doğrulanacak belge sayfa numarası. |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Doğrulanacak belge sayfa numarası. |
| [getPagesSetup()](#getPagesSetup--) | Doğrulanacak sayfaları belirlemek için Sayfa Seçenekleri. |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | Doğrulanacak sayfaları belirlemek için Sayfa Seçenekleri. |
| [getAllPages()](#getAllPages--) | Her belge sayfasını doğrulamak için bayrak. |
| [setAllPages(boolean value)](#setAllPages-boolean-) | Her belge sayfasını doğrulamak için bayrak. |
| [getExtensions()](#getExtensions--) | Alternatif imza seçenekleri doğrulaması için ek uzantılar. |
| [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | Alternatif imza seçenekleri doğrulaması için ek uzantılar. |
| [toString()](#toString--) | Dize dönüşümünü geçersiz kılar. |
### isValid() {#isValid--}
```
public final boolean isValid()
```


Geçerli özellik bayrağı.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Geçerli özellik bayrağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Doğrulanacak Belge Sayfa Numarası. Özellik ayarlanmamışsa - Belgenin tüm Sayfaları ilk oluşum için doğrulanacaktır. Minimum değer 1.

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


Doğrulanacak Belge Sayfa Numarası. Özellik ayarlanmamışsa - Belgenin tüm Sayfaları ilk oluşum için doğrulanacaktır. Minimum değer 1.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


Doğrulanacak sayfaları belirlemek için Sayfa Seçenekleri.

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


Doğrulanacak sayfaları belirlemek için Sayfa Seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


Her belge sayfasını doğrulamak için bayrak. Varsayılan değer true'dur.

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


Her belge sayfasını doğrulamak için bayrak. Varsayılan değer true'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


Alternatif imza seçenekleri doğrulaması için ek uzantılar.

**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


Alternatif imza seçenekleri doğrulaması için ek uzantılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


Dize dönüşümünü geçersiz kılar.

**Returns:**
java.lang.String -
