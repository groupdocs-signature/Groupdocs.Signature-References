---
title: "SignOptions"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "İmza seçeneklerini temsil eder."
type: docs
weight: 16
url: /tr/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

İmza seçeneklerini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | İmzalama için belge sayfa numarasını alır veya ayarlar. |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | İmzalama için belge sayfa numarasını alır veya ayarlar. |
|
|  | [getAllPages()](#getAllPages--) | İmzayı tüm belge sayfalarına yerleştir. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | İmzayı tüm belge sayfalarına yerleştir. |
|
|  | [getAppearance()](#getAppearance--) | Ek imza görünümü. |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | Ek imza görünümü. |
|
|  | [getExtensions()](#getExtensions--) | İmza Uzantıları. |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | İmza Uzantıları. |
|
|  | [getPagesSetup()](#getPagesSetup--) | İmzalanacak sayfaları belirtmek için seçenekler. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | İmzalanacak sayfaları belirtmek için seçenekler. |
|
|  | [getSignatureType()](#getSignatureType--) | İmza Türünü alın [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | İmza Seçeneklerinin Belge Türünü al veya ayarla [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | İmza Seçeneklerinin Belge Türünü al veya ayarla [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | Metin imzasının Z-sıra konumunu alır veya ayarlar. |
|
|  | [setZOrder(int value)](#setZOrder-int-) | Metin imzasının Z-sıra konumunu alır veya ayarlar. |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar. |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar. |
|
|  | [toString()](#toString--) | Dize dönüşümünü geçersiz kıl. |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


İmzalama için belge sayfa numarasını alır veya ayarlar.
Minimum ve varsayılan değer 1'dir.


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


İmzalama için belge sayfa numarasını alır veya ayarlar.
Minimum ve varsayılan değer 1'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


İmzayı tüm belge sayfalarına yerleştir.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


İmzayı tüm belge sayfalarına yerleştir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


Ek imza görünümü.


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


Ek imza görünümü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


İmza Uzantıları.


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


İmza Uzantıları.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


İmzalanacak sayfaları belirtmek için seçenekler.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


İmzalanacak sayfaları belirtmek için seçenekler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


İmza Türünü alın [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


İmza Seçeneklerinin Belge Türünü al veya ayarla [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


İmza Seçeneklerinin Belge Türünü al veya ayarla [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


Metin imzasının Z-sıra konumunu alır veya ayarlar.
Üst üste gelen imzaların görüntüleme sırasını belirler.


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


Metin imzasının Z-sıra konumunu alır veya ayarlar.
Üst üste gelen imzaların görüntüleme sırasını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar.
PDF dosyalarındaki dijital imzalar için yalnızca desteklenir.
Değer, [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm) üzerindeki sabitlerden biridir.


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


Kriptografik işlemler için kullanılacak hash algoritmasını alır veya ayarlar.
PDF dosyalarındaki dijital imzalar için yalnızca desteklenir.


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
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
