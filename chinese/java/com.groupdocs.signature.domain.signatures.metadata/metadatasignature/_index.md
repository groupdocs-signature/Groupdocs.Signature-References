---
title: "MetadataSignature"
second_title: "GroupDocs.Signature for Java API 参考"
description: "包含元数据签名属性。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

包含元数据签名属性。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getName()](#getName--) | 指定唯一的元数据名称. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 指定唯一的元数据名称. |
|
|  | [getValue()](#getValue--) | 指定元数据对象. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 指定元数据对象. |
|
|  | [getType()](#getType--) | 指定元数据值类型. |
|
|  | [setType(int value)](#setType-int-) | 指定元数据值类型. |
|
|  | [getDataEncryption()](#getDataEncryption--) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以编码和解码签名 Value 属性. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以编码和解码签名 Value 属性. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | 在反序列化后从元数据签名 Value 获取对象. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 在反序列化后从元数据签名 Text 获取对象. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较签名属性 |
|
|  | [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法 |
|
|  | [toBoolean()](#toBoolean--) | 转换为布尔值. |
|
|  | [toInteger()](#toInteger--) | 转换为整数. |
|
|  | [toDouble()](#toDouble--) | 转换为 Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | 转换为 Double. |
|
|  | [toSingle()](#toSingle--) | 转换为 float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | 转换为 float. |
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
|  | [deepClone()](#deepClone--) | 克隆 Metadata Signature 实例。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 使用给定值克隆元数据签名实例。 |
|
### getName() {#getName--}
```
public final String getName()
```


指定唯一的元数据名称.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


指定唯一的元数据名称.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


指定元数据对象.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


指定元数据对象.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


指定元数据值类型.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


指定元数据值类型.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以编码和解码签名 Value 属性.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


获取或设置 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 接口的实现，以编码和解码签名 Value 属性.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


在反序列化后从元数据签名 Value 获取对象.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - T 对象的实例


T
: 从元数据值反序列化的对象类型

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


在反序列化后从元数据签名 Text 获取对象.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | 设置自定义数据加密实现 |


T
: 从元数据值反序列化的对象类型
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


转换为 Double.


**Returns:**
double - 将元数据签名值作为 Double 返回。

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


转换为 float.


**Returns:**
float - 将元数据签名值作为 float 返回。

<br />

*** ** * ** ***

如果无法转换元数据值，则抛出异常。如果原始值是基于字符串的，则将使用 SignatureSettings 属性中的默认文化属性信息 SignatureSettings.DefaultCulture()。

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

将布尔属性转换为 "True" 或 "False"。对于其他数据类型，将使用默认的数据格式提供程序。

<br />


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


使用给定值克隆元数据签名实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.Object | 新克隆对象的值。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

