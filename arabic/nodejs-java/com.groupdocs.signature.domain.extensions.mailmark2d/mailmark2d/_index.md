---
title: "Mailmark2D"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "فئة لتشفير وفك تشفير النص المضمن في Royal Mail 2D Mailmark"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

فئة لتشفير وفك تشفير النص المضمن في Royal Mail 2D Mailmark
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | ينشئ بيانات Royal Mail Mailmark المدمجة مع قيم البيانات الأولية والثانوية الافتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [getInformationTypeID()](#getInformationTypeID--) | يحدد حمولة الباركود Royal Mail Mailmark لكل نوع منتج. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | يحدد حمولة الباركود Royal Mail Mailmark لكل نوع منتج. |
| [getVersionID()](#getVersionID--) | يحدد إصدار الباركود وفقًا لكل معرف نوع المعلومات. |
| [getClass_()](#getClass---) | يحدد فئة العنصر. |
| [setClass(String value)](#setClass-java.lang.String-) | يحدد فئة العنصر. |
| [getSupplyChainID()](#getSupplyChainID--) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. |
| [getItemID()](#getItemID--) | يحدد العنصر الفريد داخل معرف سلسلة التوريد. |
| [setItemID(int value)](#setItemID-int-) | يحدد العنصر الفريد داخل معرف سلسلة التوريد. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي. |
| [getRTSFlag()](#getRTSFlag--) | علامة تشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | علامة تشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. |
| [getCustomerContent()](#getCustomerContent--) | مساحة اختيارية لاستخدام العميل. |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | مساحة اختيارية لاستخدام العميل. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | وضع الترميز لباركود DataMatrix. |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | وضع الترميز لباركود DataMatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix. |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix. |
| [deepClone()](#deepClone--) | يحصل على نسخة من هذا الكائن. |
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


يحدد حمولة الباركود Royal Mail Mailmark لكل نوع منتج.

--------------------

القيم الصالحة: "0" - محلي مُفرز وغير مُفرز "A" - بريد عبر الإنترنت "B" - فرانكينغ "C" - تجميع

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


يحدد حمولة الباركود Royal Mail Mailmark لكل نوع منتج.

--------------------

القيم الصالحة: "0" - محلي مُفرز وغير مُفرز "A" - بريد عبر الإنترنت "B" - فرانكينغ "C" - تجميع

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


يحدد إصدار الباركود وفقًا لكل معرف نوع المعلومات.

--------------------

القيم الصالحة: "1" - يُستخدم حاليًا فقط هذه القيمة (الافتراضية) "0" و "2" إلى "9" و "A" إلى "Z" محجوزة للاستخدام المستقبلي المحتمل.

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


يحدد فئة العنصر.

--------------------

القيم الصالحة: "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - اقتصاد (تجزئة) "5" - مؤجل (تجزئة) "8" - مميز (الوصول إلى الشبكة) "9" - قياسي (الوصول إلى الشبكة)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


يحدد فئة العنصر.

--------------------

القيم الصالحة: "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - اقتصاد (تجزئة) "5" - مؤجل (تجزئة) "8" - مميز (الوصول إلى الشبكة) "9" - قياسي (الوصول إلى الشبكة)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. الحد الأقصى للقيمة: 9999999.

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. الحد الأقصى للقيمة: 9999999.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


يحدد العنصر الفريد داخل معرف سلسلة التوريد. يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن تحديده بشكل فريد لمدة لا تقل عن 90 يومًا. الحد الأقصى للقيمة: 99999999.

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


يحدد العنصر الفريد داخل معرف سلسلة التوريد. يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن تحديده بشكل فريد لمدة لا تقل عن 90 يومًا. الحد الأقصى للقيمة: 99999999.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي. المنطقة (حرف أو حرفان) المقاطعة (حرف أو حرفان) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي و DPS مع تنسيق PAF® صالح. الحد الأقصى للطول هو 9.

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


يحتوي على الرمز البريدي لعنوان التسليم مع DPS. إذا كان داخليًا، يحتوي الرمز البريدي/DP على عدد الأحرف التالي. المنطقة (حرف أو حرفان) المقاطعة (حرف أو حرفان) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي و DPS مع تنسيق PAF® صالح. الحد الأقصى للطول هو 9.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


علامة تشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. الحد الأقصى للطول هو 1

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


علامة تشير إلى مستوى خدمة الإرجاع إلى المرسل المطلوب. الحد الأقصى للطول هو 1

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®.

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


يحتوي على رمز البريد للإرجاع إلى المرسل ولكن بدون DPS. يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


مساحة اختيارية لاستخدام العميل.

--------------------

الحد الأقصى للطول حسب النوع [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


مساحة اختيارية لاستخدام العميل.

--------------------

الحد الأقصى للطول حسب النوع [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): النوع 7: 6 أحرف النوع 9: 45 حرفًا النوع 29: 25 حرفًا

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


نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix.

**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


نوع Mailmark ثنائي الأبعاد يحدد حجم باركود Data Matrix.

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
