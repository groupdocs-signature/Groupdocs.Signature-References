---
title: "ProcessLog"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示文档处理细节。"
type: docs
weight: 15
url: /zh/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

表示文档处理细节。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getDate()](#getDate--) | 获取处理的日期和时间。 |
|
|  | [getType()](#getType--) | 获取处理类型。 |
|
|  | [getMessage()](#getMessage--) | 获取处理描述。 |
|
|  | [getSucceeded()](#getSucceeded--) | 成功处理的签名数量。 |
|
|  | [getFailed()](#getFailed--) | 处理期间失败的签名数量。 |
|
|  | [getSignatures()](#getSignatures--) | 成功处理的签名列表。 |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


获取处理的日期和时间。


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


获取处理类型。


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


获取处理描述。


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


成功处理的签名数量。


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


处理期间失败的签名数量。


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


成功处理的签名列表。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
