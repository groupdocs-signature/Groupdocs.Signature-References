---
title: "SearchResult"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belirtilen belgede imzalar için aramanın sonucu."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Belirtilen belgede imzalar için aramanın sonucu.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Arama işleminin yürütme süresini milisaniye cinsinden döndürür. |
| [getTotalSignatures()](#getTotalSignatures--) | Arama işlemi tarafından işlenen toplam imzaları döndürür. |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belge boyutunu döndürür |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Hedef belgenin boyutunu döndürür. |
| [getSucceeded()](#getSucceeded--) | Bulunan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | Arama kriterlerine göre Arama işlemi başarısız olan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getSignatures()](#getSignatures--) | Algılanan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | İmzaların güçlü tipli listesine dönüşüm sağlar. |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Arama işleminin yürütme süresini milisaniye cinsinden döndürür.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Arama işlemi tarafından işlenen toplam imzaları döndürür.

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Kaynak belge boyutunu döndürür

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Hedef belgenin boyutunu döndürür. Arama yöntemi için her zaman 0 döndürür.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Bulunan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Bu liste her zaman Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)) özelliğine eşit olacaktır.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Arama kriterlerine göre Arama işlemi başarısız olan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Mevcut sürümde desteklenmemektedir.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Algılanan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


İmzaların güçlü tipli listesine dönüşüm sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Verilen imza tipinin listesini döndürür.

T : Listedeki imzaların tipi.
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

