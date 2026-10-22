---
title: "VerificationResult"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "用于保存验证过程结果的实例。"
type: docs
weight: 20
url: /zh/nodejs-java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

用于保存验证过程结果的实例。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getProcessingTime()](#getProcessingTime--) | 返回该过程的执行时间（毫秒）。 |
| [getTotalSignatures()](#getTotalSignatures--) | 返回已处理的签名总数。 |
| [getSourceDocumentSize()](#getSourceDocumentSize--) | 返回源文档的大小（字节）。 |
| [getDestinDocumentSize()](#getDestinDocumentSize--) | 返回目标文档的大小。 |
| [getSucceeded()](#getSucceeded--) | 成功验证的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
| [isValid()](#isValid--) | 如果验证过程成功则返回 true，否则返回 false。 |
| [setValid(boolean value)](#setValid-boolean-) | 如果验证过程成功则返回 true，否则返回 false。 |
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


返回源文档的大小（字节）。

**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


返回目标文档的大小。对于验证，此变量始终为零。

**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


成功验证的签名列表 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。当前不支持此属性。

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


如果验证过程成功则返回 true，否则返回 false。

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


如果验证过程成功则返回 true，否则返回 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

