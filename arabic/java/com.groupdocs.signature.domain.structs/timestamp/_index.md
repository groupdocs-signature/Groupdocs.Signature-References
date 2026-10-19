---
title: "الطابع الزمني"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل البيانات للحصول على الطابع الزمني من موقع طرف ثالث."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.domain.structs/timestamp/
---
**Inheritance:**
java.lang.Object
```
public class TimeStamp
```

يمثل البيانات للحصول على الطابع الزمني من موقع طرف ثالث.

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [TimeStamp()](#TimeStamp--) |  |
|  | [TimeStamp(String url, String user, String password)](#TimeStamp-java.lang.String-java.lang.String-java.lang.String-) | ينشئ بنية طابع زمني جديدة. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getUrl()](#getUrl--) | عنوان URL لموقع طرف ثالث. |
|
|  | [setUrl(String value)](#setUrl-java.lang.String-) | عنوان URL لموقع طرف ثالث. |
|
|  | [getUser()](#getUser--) | المستخدم. |
|
|  | [setUser(String value)](#setUser-java.lang.String-) | المستخدم. |
|
|  | [getPassword()](#getPassword--) | كلمة المرور. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | كلمة المرور. |
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


ينشئ بنية طابع زمني جديدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | url | java.lang.String | عنوان URL لموقع طرف ثالث. |
|
|  | user | java.lang.String | المستخدم. |
|
|  | password | java.lang.String | كلمة المرور. |
|

### getUrl() {#getUrl--}
```
public final String getUrl()
```


عنوان URL لموقع طرف ثالث.


**Returns:**
java.lang.String
### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


عنوان URL لموقع طرف ثالث.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getUser() {#getUser--}
```
public final String getUser()
```


المستخدم.


**Returns:**
java.lang.String
### setUser(String value) {#setUser-java.lang.String-}
```
public final void setUser(String value)
```


المستخدم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة المرور.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


كلمة المرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### CloneTo(TimeStamp that) {#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public void CloneTo(TimeStamp that)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj1 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |
| obj2 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

**Returns:**
boolean
