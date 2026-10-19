---
title: "时间戳"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示从第三方站点获取时间戳的数据。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.domain.structs/timestamp/
---
**Inheritance:**
java.lang.Object
```
public class TimeStamp
```

表示从第三方站点获取时间戳的数据。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TimeStamp()](#TimeStamp--) |  |
|  | [TimeStamp(String url, String user, String password)](#TimeStamp-java.lang.String-java.lang.String-java.lang.String-) | 实例化新的时间戳结构。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getUrl()](#getUrl--) | 第三方站点的 URL。 |
|
|  | [setUrl(String value)](#setUrl-java.lang.String-) | 第三方站点的 URL。 |
|
|  | [getUser()](#getUser--) | 用户。 |
|
|  | [setUser(String value)](#setUser-java.lang.String-) | 用户。 |
|
|  | [getPassword()](#getPassword--) | 密码。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 密码。 |
|
| [CloneTo(TimeStamp that)](#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [equals(TimeStamp obj1, TimeStamp obj2)](#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
### TimeStamp() {#TimeStamp--}
```
public TimeStamp()
```


### TimeStamp(String url, String user, String password) {#TimeStamp-java.lang.String-java.lang.String-java.lang.String-}
```
public TimeStamp(String url, String user, String password)
```


实例化新的时间戳结构。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 网址 | java.lang.String | 第三方站点的 URL。 |
|
|  | 用户 | java.lang.String | 用户。 |
|
|  | 密码 | java.lang.String | 密码。 |
|

### getUrl() {#getUrl--}
```
public final String getUrl()
```


第三方站点的 URL。


**Returns:**
java.lang.String
### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


第三方站点的 URL。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getUser() {#getUser--}
```
public final String getUser()
```


用户。


**Returns:**
java.lang.String
### setUser(String value) {#setUser-java.lang.String-}
```
public final void setUser(String value)
```


用户。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


密码。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


密码。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### CloneTo(TimeStamp that) {#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public void CloneTo(TimeStamp that)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| that | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### Clone() {#Clone--}
```
public TimeStamp Clone()
```




**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 对象 | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(TimeStamp obj1, TimeStamp obj2) {#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public static boolean equals(TimeStamp obj1, TimeStamp obj2)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj1 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |
| obj2 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

**Returns:**
boolean
