---
title: "SignResult"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "文档签署过程（包含新创建的签名）的结果。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

文档签署过程（包含新创建的签名）的结果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | 返回该过程的执行时间（毫秒）。 |
| [getTotalSignatures()](#getTotalSignatures--) | 返回已处理的签名总数。 |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | 返回源文档大小。 |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | 返回目标文档大小。 |
| [getSucceeded()](#getSucceeded--) | 新创建的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [getFailed()](#getFailed--) | 创建失败的签名列表。 |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


返回该过程的执行时间（毫秒）。

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


返回目标文档大小。

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


新创建的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


创建失败的签名列表。

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
