---
title: "SearchResult"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belirtilen belgede imzaları aramanın sonucu."
type: docs
weight: 16
url: /tr/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Belirtilen belgede imzaları aramanın sonucu.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | Arama işleminin yürütme süresini milisaniye cinsinden döndürür. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | Arama işlemi tarafından işlenen toplam imzaları döndürür. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | Kaynak belge boyutunu döndürür |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | Hedef belge boyutunu döndürür. |
|
|  | [getSucceeded()](#getSucceeded--) | Bulunan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | Arama kriterlerine göre Arama işlemi sırasında başarısız olan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getSignatures()](#getSignatures--) | Algılanan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | İmzaların güçlü tipli listesine dönüşüm sağlar. |
|
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


Hedef belge boyutunu döndürür. Arama yöntemi için her zaman 0 döndürür.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


Bulunan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). Bu liste her zaman şuna eşit olacaktır
İmzalar
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) özelliği.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


Arama kriterlerine göre Arama işlemi sırasında başarısız olan imzaların listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
Mevcut sürümde desteklenmiyor.


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


T
: Listede bulunan imzaların tipi.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

