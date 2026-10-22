---
title: "CryptoCurrencyTransfer"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل مستلم تحويل العملة المشفرة أو التحويل لرمز الاستجابة السريعة QR-Code."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

يمثل تحويل العملة المشفرة (مستلم أو تحويل) لرمز QR.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | يحصل أو يعيّن أحد أنواع العملات المشفرة المدعومة. |
| [setType(int value)](#setType-int-) | يحصل أو يعيّن أحد أنواع العملات المشفرة المدعومة. |
| [getAmount()](#getAmount--) | يحصل أو يعيّن مبلغ التحويل. |
| [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | يحصل أو يعيّن مبلغ التحويل. |
| [getAddress()](#getAddress--) | يحصل أو يعيّن العنوان العام للعملة المشفرة. |
| [setAddress(String value)](#setAddress-java.lang.String-) | يحصل أو يعيّن العنوان العام للعملة المشفرة. |
| [getMessage()](#getMessage--) | يحصل أو يعيّن رسالة التحويل الاختيارية. |
| [setMessage(String value)](#setMessage-java.lang.String-) | يحصل أو يعيّن رسالة التحويل الاختيارية. |
| [getCustomType()](#getCustomType--) | يحصل أو يعيّن رسالة التحويل الاختيارية. |
| [setCustomType(String value)](#setCustomType-java.lang.String-) | يحصل أو يعيّن رسالة التحويل الاختيارية. |
| [equals(Object obj)](#equals-java.lang.Object-) | يتجاوز طريقة Equals لمقارنة خصائص تحويل العملة المشفرة |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


يحصل أو يعيّن أحد أنواع العملات المشفرة المدعومة.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


يحصل أو يعيّن أحد أنواع العملات المشفرة المدعومة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


يحصل أو يعيّن مبلغ التحويل.

**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


يحصل أو يعيّن مبلغ التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


يحصل أو يعيّن العنوان العام للعملة المشفرة.

**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


يحصل أو يعيّن العنوان العام للعملة المشفرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


يحصل أو يعيّن رسالة التحويل الاختيارية.

**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


يحصل أو يعيّن رسالة التحويل الاختيارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


يحصل أو يعيّن رسالة التحويل الاختيارية.

**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


يحصل أو يعيّن رسالة التحويل الاختيارية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يتجاوز طريقة Equals لمقارنة خصائص تحويل العملة المشفرة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | كائن تحويل العملة المشفرة للمقارنة معه. |

**Returns:**
منطقي - يُرجع true إذا كان كائن تحويل العملة المشفرة الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا المثيل.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int - رمز تجزئة تحويل العملة المشفرة
