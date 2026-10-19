---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示加密货币转账接收方或用于二维码的转账。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

表示用于 QR 码的加密货币转账（接收方或转账）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getType()](#getType--) | 获取或设置受支持的加密货币类型之一。 |
|
|  | [setType(int value)](#setType-int-) | 获取或设置受支持的加密货币类型之一。 |
|
|  | [getAmount()](#getAmount--) | 获取或设置转账金额。 |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | 获取或设置转账金额。 |
|
|  | [getAddress()](#getAddress--) | 获取或设置加密货币公共地址。 |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | 获取或设置加密货币公共地址。 |
|
|  | [getMessage()](#getMessage--) | 获取或设置可选的转账信息。 |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | 获取或设置可选的转账信息。 |
|
|  | [getCustomType()](#getCustomType--) | 获取或设置可选的转账信息。 |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | 获取或设置可选的转账信息。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较加密货币转账属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


获取或设置受支持的加密货币类型之一。


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


获取或设置受支持的加密货币类型之一。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


获取或设置转账金额。


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


获取或设置转账金额。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


获取或设置加密货币公共地址。


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


获取或设置加密货币公共地址。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


获取或设置可选的转账信息。


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


获取或设置可选的转账信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


获取或设置可选的转账信息。


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


获取或设置可选的转账信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


覆盖 Equals 方法以比较加密货币转账属性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 对象 | java.lang.Object | 用于比较的加密货币转账对象。 |
|

**Returns:**
boolean - 如果传入的加密货币转账对象具有相同类型且其所有属性等于此实例的属性，则返回 true。

### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法


**Returns:**
int - 加密货币转账哈希码

