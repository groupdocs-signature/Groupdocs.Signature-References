---
title: "SwissAddress"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل عنوان الدائن أو المدين."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

يمثل عنوان الدائن أو المدين.
يمكنك إما ضبط الشارع، رقم المنزل، الرمز البريدي، والمدينة (structured address type)
أو سطر العنوان 1 و 2 (combined address elements type).

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يحصل أو يعيّن الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو |
اسم الشركة لشخص اعتباري.
|
|  | [setName(String value)](#setName-java.lang.String-) | يحصل أو يعيّن الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو |
اسم الشركة لشخص اعتباري.
|
|  | [getAddressLine1()](#getAddressLine1--) | يحصل أو يعيّن سطر العنوان 1. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | يحصل أو يعيّن سطر العنوان 1. |
|
|  | [getAddressLine2()](#getAddressLine2--) | يحصل أو يعيّن سطر العنوان 2. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | يحصل أو يعيّن سطر العنوان 2. |
|
|  | [getStreet()](#getStreet--) | يحصل أو يعيّن الشارع. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | يحصل أو يعيّن الشارع. |
|
|  | [getHouseNo()](#getHouseNo--) | يحصل أو يعيّن رقم المنزل. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | يحصل أو يعيّن رقم المنزل. |
|
|  | [getPostalCode()](#getPostalCode--) | يحصل أو يعيّن الرمز البريدي. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | يحصل أو يعيّن الرمز البريدي. |
|
|  | [getTown()](#getTown--) | يحصل أو يعيّن البلدة أو المدينة. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | يحصل أو يعيّن البلدة أو المدينة. |
|
|  | [getCountryCode()](#getCountryCode--) | يحصل أو يعيّن رمز البلد ISO المكوّن من حرفين. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | يحصل أو يعيّن رمز البلد ISO المكوّن من حرفين. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


يحصل أو يعيّن الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو
اسم الشركة لشخص اعتباري.
القيمة: الاسم.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحصل أو يعيّن الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو
اسم الشركة لشخص اعتباري.
القيمة: الاسم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


يحصل أو يعيّن سطر العنوان 1.
سطر العنوان 1 يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد.
هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة وهو اختياري.
القيمة: سطر العنوان 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


يحصل أو يعيّن سطر العنوان 1.
سطر العنوان 1 يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد.
هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة وهو اختياري.
القيمة: سطر العنوان 1.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


يحصل أو يعيّن سطر العنوان 2.
سطر العنوان 2 يحتوي على الرمز البريدي والبلدة.
هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.
القيمة: سطر العنوان 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


يحصل أو يعيّن سطر العنوان 2.
سطر العنوان 2 يحتوي على الرمز البريدي والبلدة.
هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.
القيمة: سطر العنوان 2.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


يحصل أو يعيّن الشارع.
يجب تحديد الشارع دون رقم المنزل.
هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.
القيمة: الشارع.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


يحصل أو يعيّن الشارع.
يجب تحديد الشارع دون رقم المنزل.
هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.
القيمة: الشارع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


يحصل أو يعيّن رقم المنزل.
هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.
القيمة: رقم المنزل.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


يحصل أو يعيّن رقم المنزل.
هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.
القيمة: رقم المنزل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


يحصل أو يعيّن الرمز البريدي.
هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.
القيمة: الرمز البريدي.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


يحصل أو يعيّن الرمز البريدي.
هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.
القيمة: الرمز البريدي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


يحصل أو يعيّن البلدة أو المدينة.
هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.
القيمة: البلدة أو المدينة.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


يحصل أو يعيّن البلدة أو المدينة.
هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.
القيمة: البلدة أو المدينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


يحصل أو يعيّن رمز البلد ISO المكوّن من حرفين.
رمز البلد إلزامي ما لم يحتوي العنوان بالكامل على قيم فارغة أو null.
القيمة: رمز البلد ISO.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


يحصل أو يعيّن رمز البلد ISO المكوّن من حرفين.
رمز البلد إلزامي ما لم يحتوي العنوان بالكامل على قيم فارغة أو null.
القيمة: رمز البلد ISO.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

