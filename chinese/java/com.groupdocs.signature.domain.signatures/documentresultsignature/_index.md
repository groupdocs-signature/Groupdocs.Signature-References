---
title: "DocumentResultSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "对包含新创建签名的文档进行归档文档签名处理的结果。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

对包含新创建签名的文档进行归档文档签名处理的结果。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getFileName()](#getFileName--) | 文档文件名 |
|
|  | [getProcessingTime()](#getProcessingTime--) | 返回该过程的执行时间（毫秒） |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 返回已处理的签名总数 |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 返回源文档大小 |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 返回目标文档大小 |
|
|  | [getSucceeded()](#getSucceeded--) | 成功处理的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getFailed()](#getFailed--) | 在处理过程中失败的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
|  | [getErrorMessage()](#getErrorMessage--) | 如果文档处理出错，此属性将包含错误信息 |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


文档文件名


**Returns:**
java.lang.String
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


返回该过程的执行时间（毫秒）


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


返回已处理的签名总数


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


返回源文档大小


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


返回目标文档大小


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


成功处理的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


在处理过程中失败的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


如果文档处理出错，此属性将包含错误信息


**Returns:**
java.lang.String
