---
title: "SMS"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示短信服务详细信息。"
type: docs
weight: 18
url: /zh/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/sms/
---
**Inheritance:**
java.lang.Object
```
public class SMS
```

表示短信服务详细信息。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SMS()](#SMS--) | 创建具有默认值的 VCard 实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumber()](#getNumber--) | 获取或设置 SMS 收件人电话号码。 |
| [setNumber(String value)](#setNumber-java.lang.String-) | 获取或设置 SMS 收件人电话号码。 |
| [getMessage()](#getMessage--) | 获取或设置 SMS 消息内容。 |
| [setMessage(String value)](#setMessage-java.lang.String-) | 获取或设置 SMS 消息内容。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 覆盖 Equals 方法以比较 SMS 属性 |
| [hashCode()](#hashCode--) | 覆盖 GetHashCode 方法。 |
### SMS() {#SMS--}
```
public SMS()
```


创建具有默认值的 VCard 实例。

### getNumber() {#getNumber--}
```
public final String getNumber()
```


获取或设置 SMS 收件人电话号码。

**Returns:**
java.lang.String
### setNumber(String value) {#setNumber-java.lang.String-}
```
public final void setNumber(String value)
```


获取或设置 SMS 收件人电话号码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


获取或设置 SMS 消息内容。

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


获取或设置 SMS 消息内容。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


覆盖 Equals 方法以比较 SMS 属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 SMS 对象。 |

**Returns:**
boolean - 如果传入的 SMS 对象具有相同类型且其所有属性等于此实例的属性，则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


覆盖 GetHashCode 方法。

**Returns:**
int - VCard 哈希码
