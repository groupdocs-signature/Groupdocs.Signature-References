---
title: "HIBCLICPrimaryData"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "用于存储 HIBC 医疗行业条码委员会 LIC 许可标识码主要数据的类。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

用于存储 HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）主数据的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | 默认构造函数() |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | 标识标签者识别码的日期。 |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | 标识标签者识别码的日期。 |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | 标识产品或目录编号。 |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | 标识产品或目录编号。 |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | 标识计量单位 ID。 |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | 标识计量单位 ID。 |
| [deepClone()](#deepClone--) | 获取此对象的副本。 |
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


默认构造函数()

### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且首字符必须为字母。

**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且首字符必须为字母。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。

**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。

**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。

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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
