---
title: "Mailmark2D"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "فئة لتشفير وفك تشفير النص المدمج في Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

فئة لتشفير وفك تشفير النص المدمج في Royal Mail 2D Mailmark

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | ينشئ بيانات Royal Mail Mailmark المدمجة مع قيم البيانات الأولية والثانوية الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | يحدد حمولة الباركود Royal Mail Mailmark لكل نوع من المنتجات. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | يحدد حمولة الباركود Royal Mail Mailmark لكل نوع من المنتجات. |
|
|  | [getVersionID()](#getVersionID--) | يحدد إصدار الباركود وفقًا لكل معرف نوع المعلومات. |
|
|  | [getClass_()](#getClass---) | يحدد فئة العنصر. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | يحدد فئة العنصر. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. |
|
|  | [getItemID()](#getItemID--) | يحدد العنصر الفريد داخل معرف سلسلة التوريد. |
|
|  | [setItemID(int value)](#setItemID-int-) | يحدد العنصر الفريد داخل معرف سلسلة التوريد. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | يحتوي على الرمز البريدي لعنوان التسليم مع DPS |
إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | يحتوي على الرمز البريدي لعنوان التسليم مع DPS |
إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي.
|
|  | [getRTSFlag()](#getRTSFlag--) | العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. |
|
|  | [getCustomerContent()](#getCustomerContent--) | مساحة اختيارية لاستخدام العميل. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | مساحة اختيارية لاستخدام العميل. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | وضع الترميز لباركود DataMatrix. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | وضع الترميز لباركود DataMatrix. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | نوع 2D Mailmark يحدد حجم باركود Data Matrix. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | نوع 2D Mailmark يحدد حجم باركود Data Matrix. |
|
|  | [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


ينشئ بيانات Royal Mail Mailmark المدمجة مع قيم البيانات الأولية والثانوية الافتراضية.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


يحدد حمولة الباركود Royal Mail Mailmark لكل نوع من المنتجات.

<br />

*** ** * ** ***

القيم الصالحة: \"0\" - محلي مُرتب وغير مُرتب \"A\" - بريد عبر الإنترنت \"B\" - طباعة الفواتير \"C\" - تجميع

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


يحدد حمولة الباركود Royal Mail Mailmark لكل نوع من المنتجات.

<br />

*** ** * ** ***

القيم الصالحة: \"0\" - محلي مُرتب وغير مُرتب \"A\" - بريد عبر الإنترنت \"B\" - طباعة الفواتير \"C\" - تجميع

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


يحدد إصدار الباركود وفقًا لكل معرف نوع المعلومات.

<br />

*** ** * ** ***

القيم الصالحة: \"1\" - يُستخدم حالياً فقط هذه القيمة (الافتراضية) \"0\" و \"2\" إلى \"9\" و \"A\" إلى \"Z\" محجوزة للاستخدام المستقبلي المحتمل.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


يحدد فئة العنصر.

<br />

*** ** * ** ***

القيم الصالحة: \"1\" - 1C (تجزئة) \"2\" - 2C (تجزئة) \"3\" - اقتصاد (تجزئة) \"5\" - مؤجل (تجزئة) \"8\" - مميز (وصول إلى الشبكة) \"9\" - قياسي (وصول إلى الشبكة)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


يحدد فئة العنصر.

<br />

*** ** * ** ***

القيم الصالحة: \"1\" - 1C (تجزئة) \"2\" - 2C (تجزئة) \"3\" - اقتصاد (تجزئة) \"5\" - مؤجل (تجزئة) \"8\" - مميز (وصول إلى الشبكة) \"9\" - قياسي (وصول إلى الشبكة)

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال.
القيمة القصوى: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال.
القيمة القصوى: 9999999.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


يحدد العنصر الفريد داخل معرف سلسلة التوريد.
يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن التعرف عليه بشكل فريد لمدة لا تقل عن 90 يومًا.
القيمة القصوى: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


يحدد العنصر الفريد داخل معرف سلسلة التوريد.
يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن التعرف عليه بشكل فريد لمدة لا تقل عن 90 يومًا.
القيمة القصوى: 99999999.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


يحتوي على الرمز البريدي لعنوان التسليم مع DPS
إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي.
المنطقة (حرف أو حرفين)
المقاطعة (حرف أو حرفين)
القطاع (حرف واحد)
الوحدة (حرفين)
DPS (حرفين).
يجب أن يتوافق الرمز البريدي و DPS مع تنسيق PAF® صالح. الحد الأقصى للطول هو 9.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


يحتوي على الرمز البريدي لعنوان التسليم مع DPS
إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي.
المنطقة (حرف أو حرفين)
المقاطعة (حرف أو حرفين)
القطاع (حرف واحد)
الوحدة (حرفين)
DPS (حرفين).
يجب أن يتوافق الرمز البريدي و DPS مع تنسيق PAF® صالح. الحد الأقصى للطول هو 9.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. الحد الأقصى للطول هو 1


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


العلم الذي يشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. الحد الأقصى للطول هو 1


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS.
يجب أن يتوافق PC (بدون DPS) مع تنسيق PAF®.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS.
يجب أن يتوافق PC (بدون DPS) مع تنسيق PAF®.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


مساحة اختيارية لاستخدام العميل.

<br />

*** ** * ** ***

الحد الأقصى للطول حسب النوع [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


مساحة اختيارية لاستخدام العميل.

<br />

*** ** * ** ***

الحد الأقصى للطول حسب النوع [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


وضع الترميز لباركود DataMatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


وضع الترميز لباركود DataMatrix. القيمة الافتراضية: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


نوع 2D Mailmark يحدد حجم باركود Data Matrix.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


نوع 2D Mailmark يحدد حجم باركود Data Matrix.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


يحصل على نسخة من هذا الكائن.


**Returns:**
java.lang.Object
