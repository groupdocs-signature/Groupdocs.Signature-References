---
title: "DeleteResult"
second_title: "GroupDocs.Signature for Java API 参考"
description: "文档中签名删除的结果。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

文档中签名删除的结果。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | 返回过程的执行时间（毫秒）。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 返回已处理的签名总数。 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 返回源文档大小。 |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 返回更新后的文档大小。 |
|
|  | [getSucceeded()](#getSucceeded--) | 成功删除的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | 未删除的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


返回过程的执行时间（毫秒）。


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


返回已处理的签名总数。


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


返回更新后的文档大小。


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


成功删除的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


未删除的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
