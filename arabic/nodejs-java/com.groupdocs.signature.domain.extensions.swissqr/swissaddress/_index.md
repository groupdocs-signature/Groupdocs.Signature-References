---
title: "SwissAddress"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل عنوان الدائن أو المدين."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

يمثل عنوان الدائن أو المدين. يمكنك إما تعيين الشارع، رقم المنزل، الرمز البريدي، والمدينة (نوع العنوان المهيكل) أو السطر الأول والثاني من العنوان (نوع العناصر المدمجة للعنوان).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يسترجع أو يعيّن الاسم، إما الاسم الأول واللقب لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [setName(String value)](#setName-java.lang.String-) | يسترجع أو يعيّن الاسم، إما الاسم الأول واللقب لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [getAddressLine1()](#getAddressLine1--) | يسترجع أو يعيّن السطر الأول من العنوان. |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | يسترجع أو يعيّن السطر الأول من العنوان. |
| [getAddressLine2()](#getAddressLine2--) | يسترجع أو يعيّن السطر الثاني من العنوان. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | يسترجع أو يعيّن السطر الثاني من العنوان. |
| [getStreet()](#getStreet--) | يسترجع أو يعيّن الشارع. |
| [setStreet(String value)](#setStreet-java.lang.String-) | يسترجع أو يعيّن الشارع. |
| [getHouseNo()](#getHouseNo--) | يسترجع أو يعيّن رقم المنزل. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | يسترجع أو يعيّن رقم المنزل. |
| [getPostalCode()](#getPostalCode--) | يسترجع أو يعيّن الرمز البريدي. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | يسترجع أو يعيّن الرمز البريدي. |
| [getTown()](#getTown--) | يسترجع أو يعيّن المدينة أو البلدة. |
| [setTown(String value)](#setTown-java.lang.String-) | يسترجع أو يعيّن المدينة أو البلدة. |
| [getCountryCode()](#getCountryCode--) | يسترجع أو يعيّن رمز الدولة ISO المكوّن من حرفين. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | يسترجع أو يعيّن رمز الدولة ISO المكوّن من حرفين. |
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


يسترجع أو يعيّن الاسم، إما الاسم الأول واللقب لشخص طبيعي أو اسم الشركة لشخص قانوني.

القيمة: الاسم.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يسترجع أو يعيّن الاسم، إما الاسم الأول واللقب لشخص طبيعي أو اسم الشركة لشخص قانوني.

القيمة: الاسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


يسترجع أو يعيّن السطر الأول من العنوان. يحتوي السطر الأول من العنوان على اسم الشارع، رقم المنزل أو صندوق البريد. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة وهو اختياري.

القيمة: السطر الأول من العنوان.

**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


يسترجع أو يعيّن السطر الأول من العنوان. يحتوي السطر الأول من العنوان على اسم الشارع، رقم المنزل أو صندوق البريد. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة وهو اختياري.

القيمة: السطر الأول من العنوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


يحصل أو يعيّن سطر العنوان 2. سطر العنوان 2 يحتوي على الرمز البريدي والمدينة. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

القيمة: سطر العنوان 2.

**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


يحصل أو يعيّن سطر العنوان 2. سطر العنوان 2 يحتوي على الرمز البريدي والمدينة. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

القيمة: سطر العنوان 2.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


يحصل أو يعيّن الشارع. يجب تحديد الشارع بدون رقم المنزل. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: الشارع.

**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


يحصل أو يعيّن الشارع. يجب تحديد الشارع بدون رقم المنزل. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: الشارع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


يحصل أو يعيّن رقم المنزل. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: رقم المنزل.

**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


يحصل أو يعيّن رقم المنزل. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: رقم المنزل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


يحصل أو يعيّن الرمز البريدي. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: الرمز البريدي.

**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


يحصل أو يعيّن الرمز البريدي. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: الرمز البريدي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


يحصل أو يعيّن المدينة أو البلدة. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: المدينة أو البلدة.

**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


يحصل أو يعيّن المدينة أو البلدة. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: المدينة أو البلدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


يحصل أو يعيّن رمز الدولة ISO المكوّن من حرفين. رمز الدولة إلزامي ما لم يحتوي العنوان بالكامل على قيم فارغة أو null.

القيمة: رمز الدولة ISO.

**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


يحصل أو يعيّن رمز الدولة ISO المكوّن من حرفين. رمز الدولة إلزامي ما لم يحتوي العنوان بالكامل على قيم فارغة أو null.

القيمة: رمز الدولة ISO.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

