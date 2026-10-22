---
title: "HIBCLICSecondaryAdditionalData"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "用于存储 HIBC（医疗行业条码委员会）LIC（授权识别码）二级及附加数据的类。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

用于存储 HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）次要及附加数据的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | 默认构造函数() |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | 标识有效期日期格式。 |
| [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | 标识有效期日期格式。 |
| [getExpiryDate()](#getExpiryDate--) | 标识有效期日期。 |
| [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | 标识有效期日期。 |
| [getLotNumber()](#getLotNumber--) | 标识批次或批号。 |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | 标识批次或批号。 |
| [getSerialNumber()](#getSerialNumber--) | 标识序列号。 |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 标识序列号。 |
| [getDateOfManufacture()](#getDateOfManufacture--) | 标识生产日期。 |
| [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | 标识生产日期。 |
| [getQuantity()](#getQuantity--) | 标识数量，必须是 0 到 500 的整数值。 |
| [setQuantity(int value)](#setQuantity-int-) | 标识数量，必须是 0 到 500 的整数值。 |
| [getLinkCharacter()](#getLinkCharacter--) | 标识输出字符串中的链接字符。 |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | 标识输出字符串中的链接字符。 |
| [deepClone()](#deepClone--) | 获取此对象的副本。 |
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


默认构造函数()

### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


标识有效期日期格式。

**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


标识有效期日期格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


标识有效期日期。如果 ExpiryDateFormat 未设置为 None，则使用此项。

**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


标识有效期日期。如果 ExpiryDateFormat 未设置为 None，则使用此项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


标识批次或批号。批次/批号必须是最长 18 个字符的字母数字字符串。

**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


标识批次或批号。批次/批号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


标识序列号。序列号必须是最长 18 个字符的字母数字字符串。

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


标识序列号。序列号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


标识生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue。

**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


标识生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1。

**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


标识输出字符串中的链接字符。

**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


标识输出字符串中的链接字符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


获取此对象的副本。

**Returns:**
java.lang.Object
