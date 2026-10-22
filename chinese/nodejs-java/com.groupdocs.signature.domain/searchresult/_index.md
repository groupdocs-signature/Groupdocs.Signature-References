---
title: "SearchResult"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "在指定文档中搜索签名的结果。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

在指定文档中搜索签名的结果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | 返回搜索过程的执行时间（毫秒）。 |
| [getTotalSignatures()](#getTotalSignatures--) | 返回搜索过程处理的签名总数。 |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | 返回源文档大小。 |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | 返回目标文档的大小。 |
| [getSucceeded()](#getSucceeded--) | 找到的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [getFailed()](#getFailed--) | 因搜索条件导致搜索过程失败的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [getSignatures()](#getSignatures--) | 检测到的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | 提供转换为强类型签名列表的功能。 |
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


返回搜索过程的执行时间（毫秒）。

**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


返回搜索过程处理的签名总数。

**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


返回源文档大小。

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


返回目标文档的大小。对于 Search 方法，它始终返回 0。

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


找到的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。此列表将始终等于 Signatures (\#getSignatures.getSignatures/\#setSignatures(List).setSignatures(List)) 属性。

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


因搜索条件导致搜索过程失败的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。当前版本不支持。

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


检测到的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


提供转换为强类型签名列表的功能。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - 返回给定签名类型的列表。

T : 列表中签名的类型。
### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

