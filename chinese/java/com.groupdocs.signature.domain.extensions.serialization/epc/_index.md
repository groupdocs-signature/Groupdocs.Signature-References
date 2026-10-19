---
title: "EPC"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示欧洲支付委员会快速响应码。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

表示欧洲支付委员会快速响应码。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [EPC()](#EPC--) | 实例化新的 EPC 对象。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 获取或设置受益人名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 获取或设置受益人名称。 |
|
|  | [getBIC()](#getBIC--) | 获取或设置受益人的 BIC（最长 11 个字符）。 |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | 获取或设置受益人的 BIC（最长 11 个字符）。 |
|
|  | [getIBAN()](#getIBAN--) | 获取或设置受益人的账户（IBAN）。 |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | 获取或设置受益人的账户（IBAN）。 |
|
|  | [getAmount()](#getAmount--) | 获取或设置金额。 |
|
|  | [setAmount(double value)](#setAmount-double-) | 获取或设置金额。 |
|
|  | [getCode()](#getCode--) | 获取或设置业务代码（最多 4 个字符）。 |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | 获取或设置业务代码（最多 4 个字符）。 |
|
|  | [getReference()](#getReference--) | 获取或设置付款参考（最多 35 个字符）。 |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | 获取或设置付款参考（最多 35 个字符）。 |
|
|  | [getRemittance()](#getRemittance--) | 获取或设置汇款信息（最多 140 个字符）。 |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | 获取或设置汇款信息（最多 140 个字符）。 |
|
|  | [getInformation()](#getInformation--) | 获取或设置提示信息。 |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | 获取或设置提示信息。 |
|
|  | [getVersion()](#getVersion--) | EPC / SEPA QR-Code 版本实现。 |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QR-Code 版本实现。 |
|
|  | [getCharset()](#getCharset--) | EPC / SEPA QR-Code 字符集实现。 |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QR-Code 字符集实现。 |
|
|  | [getIdentification()](#getIdentification--) | EPC / SEPA QR-Code 标识。 |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QR-Code 标识。 |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较 EPC 属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
### EPC() {#EPC--}
```
public EPC()
```


实例化新的 EPC 对象。


### getName() {#getName--}
```
public final String getName()
```


获取或设置受益人的名称。最大长度为 70 个字符。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置受益人的名称。最大长度为 70 个字符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


获取或设置受益人的 BIC（最长 11 个字符）。


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


获取或设置受益人的 BIC（最长 11 个字符）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


获取或设置受益人的账户（IBAN）。IBAN 最多由 34 个字母数字字符组成。


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


获取或设置受益人的账户（IBAN）。IBAN 最多由 34 个字母数字字符组成。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


获取或设置金额。


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


获取或设置金额。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


获取或设置业务代码（最多 4 个字符）。


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


获取或设置业务代码（最多 4 个字符）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


获取或设置付款参考（最大 35 个字符）。此字段与汇款信息字段互斥。


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


获取或设置付款参考（最大 35 个字符）。此字段与汇款信息字段互斥。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


获取或设置汇款信息（最大 140 个字符）。此字段与付款参考字段互斥。


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


获取或设置汇款信息（最大 140 个字符）。此字段与付款参考字段互斥。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


获取或设置提示信息。最大 70 个字符。


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


获取或设置提示信息。最大 70 个字符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Code 版本实现。默认情况下，此值设置为 002。


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Code 版本实现。默认情况下，此值设置为 002。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Code 字符集实现。默认情况下，此值设置为 1。


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Code 字符集实现。默认情况下，此值设置为 1。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Code 标识。默认情况下，此值设置为 SCT。


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Code 标识。默认情况下，此值设置为 SCT。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


覆盖 Equals 方法以比较 EPC 属性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 来源 | java.lang.Object | 用于比较的 EPC 对象。 |
|

**Returns:**
boolean - 如果传入的地址对象具有相同类型且其所有属性等于此实例的属性，则返回 true。

### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法


**Returns:**
int - Email 哈希码

