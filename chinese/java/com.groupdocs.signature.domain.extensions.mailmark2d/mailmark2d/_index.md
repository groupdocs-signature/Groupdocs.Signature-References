---
title: "Mailmark2D"
second_title: "GroupDocs.Signature for Java API 参考"
description: "用于对嵌入 Royal Mail 2D Mailmark 的文本进行编码和解码的类。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

用于对嵌入 Royal Mail 2D Mailmark 的文本进行编码和解码的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | 创建 Royal Mail Mailmark 合并数据，使用默认的主数据和次数据值。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | 标识 UPU 国家 ID。最大长度：4 个字符。 |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | 标识 UPU 国家 ID。最大长度：4 个字符。 |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | 标识每种产品类型的 Royal Mail Mailmark 条码负载。 |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | 标识每种产品类型的 Royal Mail Mailmark 条码负载。 |
|
|  | [getVersionID()](#getVersionID--) | 标识与每个信息类型 ID 相关的条码版本。 |
|
|  | [getClass_()](#getClass---) | 标识项目的类别。 |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | 标识项目的类别。 |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | 标识参与邮件投递的唯一客户群体。 |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | 标识参与邮件投递的唯一客户群体。 |
|
|  | [getItemID()](#getItemID--) | 标识供应链 ID 中的唯一项目。 |
|
|  | [setItemID(int value)](#setItemID-int-) | 标识供应链 ID 中的唯一项目。 |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | 包含带有 DPS 的收货地址邮编 |
如果是内陆，邮编/DP 包含以下字符数。
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | 包含带有 DPS 的收货地址邮编 |
如果是内陆，邮编/DP 包含以下字符数。
|
|  | [getRTSFlag()](#getRTSFlag--) | 标志，指示请求的退回寄件服务级别。 |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 标志，指示请求的退回寄件服务级别。 |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | 包含退回寄件邮编，但不包含DPS。 |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | 包含退回寄件邮编，但不包含DPS。 |
|
|  | [getCustomerContent()](#getCustomerContent--) | 供客户使用的可选空间。 |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | 供客户使用的可选空间。 |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | DataMatrix 条码的编码模式。 |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | DataMatrix 条码的编码模式。 |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark 类型定义 Data Matrix 条码的尺寸。 |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark 类型定义 Data Matrix 条码的尺寸。 |
|
|  | [deepClone()](#deepClone--) | 获取此对象的副本。 |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


创建 Royal Mail Mailmark 合并数据，使用默认的主数据和次数据值。


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


标识 UPU 国家 ID。最大长度：4 个字符。


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


标识 UPU 国家 ID。最大长度：4 个字符。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


标识每种产品类型的 Royal Mail Mailmark 条码负载。

<br />

*** ** * ** ***

有效值："0" - 国内已分类和未分类 "A" - 在线邮资 "B" - 贴票 "C" - 合并

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


标识每种产品类型的 Royal Mail Mailmark 条码负载。

<br />

*** ** * ** ***

有效值："0" - 国内已分类和未分类 "A" - 在线邮资 "B" - 贴票 "C" - 合并

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


标识与每个信息类型 ID 相关的条码版本。

<br />

*** ** * ** ***

有效值："1" - 当前仅使用此值（默认） "0" 和 "2" 到 "9" 以及 "A" 到 "Z" 为潜在的未来使用保留。

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


标识项目的类别。

<br />

*** ** * ** ***

有效值："1" - 1C（零售） "2" - 2C（零售） "3" - 经济（零售） "5" - 延期（零售） "8" - 高级（网络访问） "9" - 标准（网络访问）

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


标识项目的类别。

<br />

*** ** * ** ***

有效值："1" - 1C（零售） "2" - 2C（零售） "3" - 经济（零售） "5" - 延期（零售） "8" - 高级（网络访问） "9" - 标准（网络访问）

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


标识参与邮件投递的唯一客户群体。
最大值：9999999。


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


标识参与邮件投递的唯一客户群体。
最大值：9999999。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


标识供应链 ID 中的唯一项目。
每个 Mailmark 条码必须携带一个 ID，以便至少在 90 天内唯一识别。
最大值：99999999。


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


标识供应链 ID 中的唯一项目。
每个 Mailmark 条码必须携带一个 ID，以便至少在 90 天内唯一识别。
最大值：99999999。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


包含带有 DPS 的收货地址邮编
如果是内陆，邮编/DP 包含以下字符数。
地区（1 或 2 个字符）
区（1 或 2 个字符）
部门（1 个字符）
单元（2 个字符）
DPS（2 个字符）。
邮编和 DPS 必须符合有效的 PAF® 格式。最大长度为 9。


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


包含带有 DPS 的收货地址邮编
如果是内陆，邮编/DP 包含以下字符数。
地区（1 或 2 个字符）
区（1 或 2 个字符）
部门（1 个字符）
单元（2 个字符）
DPS（2 个字符）。
邮编和 DPS 必须符合有效的 PAF® 格式。最大长度为 9。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


标志，指示请求的退回寄件服务级别。最大长度为 1


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


标志，指示请求的退回寄件服务级别。最大长度为 1


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


包含退回寄件邮编，但不包含DPS。
PC（不含 DPS）必须符合 PAF® 格式。


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


包含退回寄件邮编，但不包含DPS。
PC（不含 DPS）必须符合 PAF® 格式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


供客户使用的可选空间。

<br />

*** ** * ** ***

按类型的最大长度 [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype)：类型 7：6 个字符 类型 9：45 个字符 类型 29：25 个字符

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


供客户使用的可选空间。

<br />

*** ** * ** ***

按类型的最大长度 [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype)：类型 7：6 个字符 类型 9：45 个字符 类型 29：25 个字符

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


DataMatrix 条码的编码模式。默认值：DataMatrixEncodeMode.C40。 [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


DataMatrix 条码的编码模式。默认值：DataMatrixEncodeMode.C40。 [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark 类型定义 Data Matrix 条码的尺寸。


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark 类型定义 Data Matrix 条码的尺寸。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


获取此对象的副本。


**Returns:**
java.lang.Object
