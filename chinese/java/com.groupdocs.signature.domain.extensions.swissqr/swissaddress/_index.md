---
title: "SwissAddress"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示债权人或债务人的地址。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

表示债权人或债务人的地址。
您可以设置街道、门牌号、邮政编码和城镇（结构化地址类型）
或地址行 1 和 2（组合地址元素类型）。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 获取或设置名称，可以是自然人的名字和姓氏，或 |
法人的公司名称。
|
|  | [setName(String value)](#setName-java.lang.String-) | 获取或设置名称，可以是自然人的名字和姓氏，或 |
法人的公司名称。
|
|  | [getAddressLine1()](#getAddressLine1--) | 获取或设置地址行 1。 |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | 获取或设置地址行 1。 |
|
|  | [getAddressLine2()](#getAddressLine2--) | 获取或设置地址行 2。 |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | 获取或设置地址行 2。 |
|
|  | [getStreet()](#getStreet--) | 获取或设置街道。 |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | 获取或设置街道。 |
|
|  | [getHouseNo()](#getHouseNo--) | 获取或设置门牌号。 |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | 获取或设置门牌号。 |
|
|  | [getPostalCode()](#getPostalCode--) | 获取或设置邮政编码。 |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 获取或设置邮政编码。 |
|
|  | [getTown()](#getTown--) | 获取或设置城镇或城市。 |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | 获取或设置城镇或城市。 |
|
|  | [getCountryCode()](#getCountryCode--) | 获取或设置两字母 ISO 国家代码。 |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 获取或设置两字母 ISO 国家代码。 |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


获取或设置名称，可以是自然人的名字和姓氏，或
法人的公司名称。
值：名称。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


获取或设置名称，可以是自然人的名字和姓氏，或
法人的公司名称。
值：名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


获取或设置地址行 1。
地址行 1 包含街道名称、门牌号或邮政信箱。
此字段仅用于组合元素地址，且为可选项。
值：地址行 1。


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


获取或设置地址行 1。
地址行 1 包含街道名称、门牌号或邮政信箱。
此字段仅用于组合元素地址，且为可选项。
值：地址行 1。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


获取或设置地址行 2。
地址行 2 包含邮政编码和城镇。
此字段仅用于组合元素地址。对于此类型，它是必填的。
值：地址行 2。


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


获取或设置地址行 2。
地址行 2 包含邮政编码和城镇。
此字段仅用于组合元素地址。对于此类型，它是必填的。
值：地址行 2。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


获取或设置街道。
街道必须在不包含门牌号的情况下指定。
此字段仅用于结构化地址，且为可选项。
值：街道。


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


获取或设置街道。
街道必须在不包含门牌号的情况下指定。
此字段仅用于结构化地址，且为可选项。
值：街道。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


获取或设置门牌号。
此字段仅用于结构化地址，且为可选项。
值：门牌号。


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


获取或设置门牌号。
此字段仅用于结构化地址，且为可选项。
值：门牌号。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


获取或设置邮政编码。
此字段仅用于结构化地址。对于此类型，它是必填的。
值：邮政编码。


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


获取或设置邮政编码。
此字段仅用于结构化地址。对于此类型，它是必填的。
值：邮政编码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


获取或设置城镇或城市。
此字段仅用于结构化地址。对于此类型，它是必填的。
值：城镇或城市。


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


获取或设置城镇或城市。
此字段仅用于结构化地址。对于此类型，它是必填的。
值：城镇或城市。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


获取或设置两字母 ISO 国家代码。
除非整个地址包含 null 或空值，否则国家代码是必填的。
值：ISO 国家代码。


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


获取或设置两字母 ISO 国家代码。
除非整个地址包含 null 或空值，否则国家代码是必填的。
值：ISO 国家代码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

