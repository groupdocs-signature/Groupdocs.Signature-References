---
title: "SymmetricEncryption"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يطبق خوارزميات متماثلة قياسية لتشفير البيانات باستخدام مفتاح واحد وملح عبارة مرور."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

ينفذ خوارزميات متماثلة قياسية لتشفير البيانات باستخدام مفتاح واحد وعبارة مرور (ملح).

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | ينشئ خوارزمية تشفير متماثلة مع المعلمات. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | ينشئ خوارزمية تشفير متماثلة باستخدام عبارة مرور افتراضية |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | يحصل أو يعيّن نوع الخوارزمية المتماثلة. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | يحصل أو يعيّن نوع الخوارزمية المتماثلة. |
|
|  | [getKey()](#getKey--) | يحصل أو يعيّن مفتاح خوارزمية التشفير. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | يحصل أو يعيّن مفتاح خوارزمية التشفير. |
|
|  | [getSalt()](#getSalt--) | يحصل أو يعيّن عبارة مرور خوارزمية التشفير. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | يحصل أو يعيّن عبارة مرور خوارزمية التشفير. |
|
|  | [encode(String source)](#encode-java.lang.String-) | يشفّر سلسلة بناءً على نوع الخوارزمية المقدَّم، المفتاح وملح المعلمات |
|
|  | [decode(String source)](#decode-java.lang.String-) | يفكّ تشفير سلسلة بناءً على نوع الخوارزمية المقدَّم، المفتاح وملح المعلمات |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


ينشئ خوارزمية تشفير متماثلة مع المعلمات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | algorithmType | int | حدد نوع الخوارزمية المتماثلة |
|
|  | key | java.lang.String | مفتاح التشفير |
|
|  | الملح | java.lang.String | عبارة مرور للتشفير |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


ينشئ خوارزمية تشفير متماثلة باستخدام عبارة مرور افتراضية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | algorithmType | int | حدد نوع الخوارزمية المتماثلة |
|
|  | key | java.lang.String | مفتاح التشفير |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


يحصل أو يعيّن نوع الخوارزمية المتماثلة.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


يحصل أو يعيّن نوع الخوارزمية المتماثلة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


يحصل أو يعيّن مفتاح خوارزمية التشفير.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


يحصل أو يعيّن مفتاح خوارزمية التشفير.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


يحصل أو يعيّن عبارة مرور خوارزمية التشفير.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


يحصل أو يعيّن عبارة مرور خوارزمية التشفير.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


يشفّر سلسلة بناءً على نوع الخوارزمية المقدَّم، المفتاح وملح المعلمات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المصدر | java.lang.String | السلسلة المصدر للتشفير. |
|

**Returns:**
java.lang.String - يُرجع السلسلة المشفرة.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


يفكّ تشفير سلسلة بناءً على نوع الخوارزمية المقدَّم، المفتاح وملح المعلمات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المصدر | java.lang.String | السلسلة المشفرة للفك. |
|

**Returns:**
java.lang.String - يُرجع السلسلة المفكوكة.

