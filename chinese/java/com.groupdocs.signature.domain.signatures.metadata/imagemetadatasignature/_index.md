---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含图像元数据签名属性。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

包含图像元数据签名属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | 创建具有 Id 和值的图像元数据签名 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getId()](#getId--) | Image Metadata 签名的标识符。 |
|
|  | [setId(int value)](#setId-int-) | Image Metadata 签名的标识符。 |
|
|  | [getSize()](#getSize--) | 只读值，用于获取元数据值的大小 |
|
|  | [setSize(int value)](#setSize-int-) | 只读值，用于获取元数据值的大小 |
|
|  | [getDescription()](#getDescription--) | 只读值，用于获取标准 Image Metadata 签名的描述 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [deepClone()](#deepClone--) | 克隆 Metadata Signature 实例。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 克隆具有给定值的 Image Metadata 签名实例。 |
|
|  | [toBoolean()](#toBoolean--) | 转换为布尔值. |
|
|  | [toInteger()](#toInteger--) | 转换为整数. |
|
|  | [toLong()](#toLong--) | 转换为 long。 |
|
|  | [toSingle()](#toSingle--) | 转换为 float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | 转换为 float. |
|
|  | [toDouble()](#toDouble--) | 转换为 Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | 转换为 Double. |
|
|  | [toDecimal()](#toDecimal--) | 转换为 Decimal。 |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | 转换为 Decimal。 |
|
|  | [toDateTime()](#toDateTime--) | 转换为 DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | 转换为 DateTime. |
|
|  | [toString()](#toString--) | 使用覆盖的 ToString() 方法转换为字符串 |
|
|  | [toString(String format)](#toString-java.lang.String-) | 使用指定格式转换为字符串 |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | 使用指定格式转换为字符串 |
|
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


创建具有 Id 和值的图像元数据签名


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 标识符 | int | 唯一标识符 Image Metadata Signature 名称。请参阅参考文献以获取 Exif 标签规范中可能的 id 值。 |
|
|  | 值 | java.lang.Object | Metadata 值 |
|

### getId() {#getId--}
```
public final int getId()
```


Image Metadata 签名的标识符。
参见包含预定义 Id 值的标准签名的 [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) 类。


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Image Metadata 签名的标识符。
参见包含预定义 Id 值的标准签名的 [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) 类。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


只读值，用于获取元数据值的大小


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


只读值，用于获取元数据值的大小


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


只读值，用于获取标准 Image Metadata 签名的描述


**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


覆盖 Equals 方法以比较签名属性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 签名 | java.lang.Object | 用于比较的签名对象。 |
|

**Returns:**
boolean - 如果传入的签名对象具有相同类型且所有属性都等于此实例的属性，则返回 true。

### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法


**Returns:**
int - 签名哈希码

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆 Metadata Signature 实例。


**Returns:**
java.lang.Object - 返回克隆的 Metadata Signature 实例

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


克隆具有给定值的 Image Metadata 签名实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.Object | 新克隆对象的值。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


转换为布尔值.


**Returns:**
boolean - 将元数据签名值作为布尔值返回。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


转换为整数.


**Returns:**
int - 将元数据签名值作为整数返回。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


转换为 long。


**Returns:**
long - 返回元数据签名值为 long。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


转换为 float.


**Returns:**
float - 返回 Image Metadata 签名值为 float。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。如果原始值是基于字符串的，则将使用 SignatureSettings 属性中的默认文化属性信息 SignatureSettings.DefaultCulture。

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


转换为 float.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 提供程序 | java.util.Locale | 用于数据转换操作的格式数据提供程序。 |

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />

|

**Returns:**
float - 将元数据签名值作为 float 返回。

### toDouble() {#toDouble--}
```
public double toDouble()
```


转换为 Double.


**Returns:**
double - 返回 Image Metadata 签名值为 Double。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。如果原始值是基于字符串的，则将使用 SignatureSettings 属性中的默认文化属性信息 SignatureSettings.DefaultCulture。

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


转换为 Double.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 提供程序 | java.util.Locale | 用于数据转换操作的格式数据提供程序。 |

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />

|

**Returns:**
double - 将元数据签名值作为 Double 返回。

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


转换为 Decimal。


**Returns:**
java.math.BigDecimal - 返回 Image Metadata 签名值为 Decimal。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。如果原始值是基于字符串的，则将使用 SignatureSettings 属性中的默认文化属性信息 SignatureSettings.DefaultCulture。

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


转换为 Decimal。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 提供程序 | java.util.Locale | 用于数据转换操作的格式数据提供程序。 |

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />

|

**Returns:**
java.math.BigDecimal - 返回元数据签名值为 Decimal。

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


转换为 DateTime.


**Returns:**
java.util.Date - 将元数据签名值作为 DateTime 返回。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。如果原始值是基于字符串的，则将使用 SignatureSettings 属性中的默认文化属性信息 SignatureSettings.DefaultCulture。

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


转换为 DateTime.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 提供程序 | java.util.Locale | 用于数据转换操作的格式数据提供程序。 |

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。

<br />

|

**Returns:**
java.util.Date - 将元数据签名值作为 DateTime 返回。

### toString() {#toString--}
```
public String toString()
```


使用覆盖的 ToString() 方法转换为字符串


**Returns:**
java.lang.String - 将元数据签名值作为 String 返回。

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


使用指定格式转换为字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 格式 | java.lang.String | 数据格式字符串。 |

<br />

*** ** * ** ***

将布尔属性转换为 "True" 或 "False"。将使用 SignatureSettings 属性中的默认文化属性信息 SignatureSettings.DefaultCulture。

<br />

|

**Returns:**
java.lang.String - 将元数据签名值作为 String 返回。

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


使用指定格式转换为字符串


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 格式 | java.lang.String | 数据格式字符串。 |
|
|  | 提供程序 | java.util.Locale | 用于数据转换操作的格式数据提供程序。 |

<br />

*** ** * ** ***

将布尔属性转换为 "True" 或 "False"。

<br />

|

**Returns:**
java.lang.String - 将元数据签名值作为 String 返回。

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

