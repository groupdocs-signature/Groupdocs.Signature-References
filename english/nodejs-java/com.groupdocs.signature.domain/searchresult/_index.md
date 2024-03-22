---
title: SearchResult
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Result of searching for signatures in specified document.
type: docs
weight: 16
url: /nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

Result of searching for signatures in specified document.
## Methods

| Method | Description |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | Returns the execution time of the search process in milliseconds. |
| [getTotalSignatures()](#getTotalSignatures--) | Returns the total processed signatures by the search process |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | Returns source document size |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | Returns destination document size. |
| [getSucceeded()](#getSucceeded--) | List of found signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [getFailed()](#getFailed--) | List of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) that failed Search process by search criteria. |
| [getSignatures()](#getSignatures--) | List of detected signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Provides conversion to strongly typed list of signatures. |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


Returns the execution time of the search process in milliseconds.

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Returns the total processed signatures by the search process

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


Returns source document size

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


Returns destination document size. For Search method it always returns 0.

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


List of found signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). This list will be always equal to  Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)) property.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


List of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) that failed Search process by search criteria. Not supported in current version.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


List of detected signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


Provides conversion to strongly typed list of signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Returns list of given signature type.

 T : The type of signatures in the list.
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

