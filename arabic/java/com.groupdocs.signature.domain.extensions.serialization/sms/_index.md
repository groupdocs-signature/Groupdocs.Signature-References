---
title: "رسالة نصية"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل تفاصيل خدمة الرسائل القصيرة SMS."
type: docs
weight: 18
url: /ar/java/com.groupdocs.signature.domain.extensions.serialization/sms/
---
**Inheritance:**
java.lang.Object
```
public class SMS
```

يمثل تفاصيل خدمة الرسائل القصيرة SMS.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [SMS()](#SMS--) | ينشئ كائن VCard بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getNumber()](#getNumber--) | يحصل أو يعيّن رقم هاتف مستلم الرسالة النصية. |
|
|  | [setNumber(String value)](#setNumber-java.lang.String-) | يحصل أو يعيّن رقم هاتف مستلم الرسالة النصية. |
|
|  | [getMessage()](#getMessage--) | يحصل أو يعيّن محتوى رسالة النصية. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | يحصل أو يعيّن محتوى رسالة النصية. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص الرسالة النصية |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
### SMS() {#SMS--}
```
public SMS()
```


ينشئ كائن VCard بالقيم الافتراضية.


### getNumber() {#getNumber--}
```
public final String getNumber()
```


يحصل أو يعيّن رقم هاتف مستلم الرسالة النصية.


**Returns:**
java.lang.String
### setNumber(String value) {#setNumber-java.lang.String-}
```
public final void setNumber(String value)
```


يحصل أو يعيّن رقم هاتف مستلم الرسالة النصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


يحصل أو يعيّن محتوى رسالة النصية.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


يحصل أو يعيّن محتوى رسالة النصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يستبدل طريقة Equals لمقارنة خصائص الرسالة النصية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | كائن الرسالة النصية للمقارنة معه. |
|

**Returns:**
منطقي - يُرجع true إذا كان كائن الرسالة النصية الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا الكائن.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يستبدل طريقة GetHashCode


**Returns:**
int - رمز التجزئة لـ VCard

