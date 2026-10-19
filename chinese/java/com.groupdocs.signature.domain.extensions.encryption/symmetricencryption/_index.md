---
title: "SymmetricEncryption"
second_title: "GroupDocs.Signature for Java API 参考"
description: "实现了使用单一密钥和密码盐进行数据加密的标准对称算法。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

实现了使用单一密钥和密码短语（盐）的标准对称数据加密算法。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | 使用参数创建对称加密算法。 |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | 使用默认密码创建对称加密算法 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | 获取或设置对称算法的类型。 |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | 获取或设置对称算法的类型。 |
|
|  | [getKey()](#getKey--) | 获取或设置加密算法的密钥。 |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | 获取或设置加密算法的密钥。 |
|
|  | [getSalt()](#getSalt--) | 获取或设置加密算法的密码短语。 |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | 获取或设置加密算法的密码短语。 |
|
|  | [encode(String source)](#encode-java.lang.String-) | 根据提供的算法类型、密钥和盐参数加密字符串 |
|
|  | [decode(String source)](#decode-java.lang.String-) | 根据提供的算法类型、密钥和盐参数解密字符串 |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


使用参数创建对称加密算法。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | algorithmType | int | 指定对称算法类型 |
|
|  | key | java.lang.String | 加密密钥 |
|
|  | 盐 | java.lang.String | 加密的密码短语 |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


使用默认密码创建对称加密算法


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | algorithmType | int | 指定对称算法类型 |
|
|  | key | java.lang.String | 加密密钥 |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


获取或设置对称算法的类型。


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


获取或设置对称算法的类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


获取或设置加密算法的密钥。


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


获取或设置加密算法的密钥。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


获取或设置加密算法的密码短语。


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


获取或设置加密算法的密码短语。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


根据提供的算法类型、密钥和盐参数加密字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 来源 | java.lang.String | 要编码的源字符串。 |
|

**Returns:**
java.lang.String - 返回加密后的字符串。

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


根据提供的算法类型、密钥和盐参数解密字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 来源 | java.lang.String | 要解码的加密字符串。 |
|

**Returns:**
java.lang.String - 返回解密后的字符串。

