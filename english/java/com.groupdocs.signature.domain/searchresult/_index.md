---
title: SearchResult
second_title: GroupDocs.Signature for Java API Reference
description: Result of searching for signatures in specified document.
type: docs
weight: 16
url: /java/com.groupdocs.signature.domain/searchresult/
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
| [getSignatures()](#getSignatures--) | List of detected signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | Provides conversion to strongly typed list of signatures. |
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
