---
title: "HIBCLICCombinedData"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "用于存储 HIBC（医疗行业条码委员会）LIC（授权识别码）合并数据的类，包含主数据和次数据实体。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.hibclic/hibcliccombineddata/
---
**Inheritance:**
java.lang.Object
```
public class HIBCLICCombinedData
```

用于存储 HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）结合主数据和次要数据实体的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HIBCLICCombinedData()](#HIBCLICCombinedData--) | 创建 HIBC（医疗行业条码委员会）LIC（授权识别码）合并数据，使用默认的主数据和次数据值。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPrimaryData()](#getPrimaryData--) | HIBC LIC 主要数据结构 |
| [setPrimaryData(HIBCLICPrimaryData value)](#setPrimaryData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICPrimaryData-) | HIBC LIC 主要数据结构 |
| [getSecondaryAdditionalData()](#getSecondaryAdditionalData--) | HIBC LIC 次要数据结构 |
| [setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value)](#setSecondaryAdditionalData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICSecondaryAdditionalData-) | HIBC LIC 次要数据结构 |
| [deepClone()](#deepClone--) | 获取此对象的副本。 |
| [getCodetext()](#getCodetext--) |  |
### HIBCLICCombinedData() {#HIBCLICCombinedData--}
```
public HIBCLICCombinedData()
```


创建 HIBC（医疗行业条码委员会）LIC（授权识别码）合并数据，使用默认的主数据和次数据值。

### getPrimaryData() {#getPrimaryData--}
```
public final HIBCLICPrimaryData getPrimaryData()
```


HIBC LIC 主要数据结构

**Returns:**
[HIBCLICPrimaryData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata)
### setPrimaryData(HIBCLICPrimaryData value) {#setPrimaryData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICPrimaryData-}
```
public final void setPrimaryData(HIBCLICPrimaryData value)
```


HIBC LIC 主要数据结构

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HIBCLICPrimaryData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata) |  |

### getSecondaryAdditionalData() {#getSecondaryAdditionalData--}
```
public final HIBCLICSecondaryAdditionalData getSecondaryAdditionalData()
```


HIBC LIC 次要数据结构

**Returns:**
[HIBCLICSecondaryAdditionalData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata)
### setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value) {#setSecondaryAdditionalData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICSecondaryAdditionalData-}
```
public final void setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value)
```


HIBC LIC 次要数据结构

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HIBCLICSecondaryAdditionalData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata) |  |

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
