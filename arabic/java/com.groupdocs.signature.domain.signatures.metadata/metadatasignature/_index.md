---
title: "MetadataSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع بيانات التعريف."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

يحتوي على خصائص توقيع بيانات التعريف.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يحدد اسم بيانات تعريف فريد. |
|
|  | [setName(String value)](#setName-java.lang.String-) | يحدد اسم بيانات تعريف فريد. |
|
|  | [getValue()](#getValue--) | يحدد كائن بيانات التعريف. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | يحدد كائن بيانات التعريف. |
|
|  | [getType()](#getType--) | يحدد نوع قيمة بيانات التعريف. |
|
|  | [setType(int value)](#setType-int-) | يحدد نوع قيمة بيانات التعريف. |
|
|  | [getDataEncryption()](#getDataEncryption--) | يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص قيمة التوقيع. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص قيمة التوقيع. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | الحصول على الكائن من قيمة توقيع البيانات التعريفية أثناء فك التسلسل. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول على الكائن من نص توقيع البيانات التعريفية أثناء فك التسلسل. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [toBoolean()](#toBoolean--) | يحوّل إلى قيمة منطقية. |
|
|  | [toInteger()](#toInteger--) | يحوّل إلى عدد صحيح. |
|
|  | [toDouble()](#toDouble--) | يحوّل إلى Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | يحوّل إلى Double. |
|
|  | [toSingle()](#toSingle--) | يحوّل إلى float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | يحوّل إلى float. |
|
|  | [toDateTime()](#toDateTime--) | يحوّل إلى DateTime. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | يحوّل إلى DateTime. |
|
|  | [toString()](#toString--) | يحوِّل إلى String باستخدام طريقة ToString() المتجاوزة |
|
|  | [toString(String format)](#toString-java.lang.String-) | يحوِّل إلى String باستخدام التنسيق المحدد |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | يحوِّل إلى String باستخدام التنسيق المحدد |
|
|  | [deepClone()](#deepClone--) | استنساخ كائن توقيع البيانات الوصفية. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ كائن Metadata Signature مع القيمة المعطاة. |
|
### getName() {#getName--}
```
public final String getName()
```


يحدد اسم بيانات تعريف فريد.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحدد اسم بيانات تعريف فريد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


يحدد كائن بيانات التعريف.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


يحدد كائن بيانات التعريف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


يحدد نوع قيمة بيانات التعريف.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


يحدد نوع قيمة بيانات التعريف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص قيمة التوقيع.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص قيمة التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


الحصول على الكائن من قيمة توقيع البيانات التعريفية أثناء فك التسلسل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - كائن من نوع T


T
: نوع الكائن لإلغاء تسلسله من قيمة Metadata

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


الحصول على الكائن من نص توقيع البيانات التعريفية أثناء فك التسلسل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | تعيين تنفيذ تشفير البيانات المخصص |


T
: نوع الكائن لإلغاء تسلسله من قيمة Metadata
|

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التوقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |
|

**Returns:**
boolean - يُعيد true إذا كان كائن التوقيع الممرّر له نفس النوع وجميع خصائصه مساوية لخصائص هذه الحالة.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يستبدل طريقة GetHashCode


**Returns:**
int - رمز التجزئة للتوقيع

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


يحوّل إلى قيمة منطقية.


**Returns:**
boolean - يُعيد قيمة توقيع Metadata كقيمة منطقية boolean.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


يحوّل إلى عدد صحيح.


**Returns:**
int - يُعيد قيمة توقيع Metadata كعدد صحيح integer.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata.

<br />


### toDouble() {#toDouble--}
```
public double toDouble()
```


يحوّل إلى Double.


**Returns:**
double - يُعيد قيمة توقيع Metadata كقيمة Double.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات الخاصية للثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


يحوّل إلى Double.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مزود | java.util.Locale | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata

<br />

|

**Returns:**
double - يُعيد قيمة توقيع Metadata كقيمة Double.

### toSingle() {#toSingle--}
```
public float toSingle()
```


يحوّل إلى float.


**Returns:**
float - يُعيد قيمة توقيع Metadata كقيمة float.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات الخاصية للثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture ()

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


يحوّل إلى float.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مزود | java.util.Locale | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata

<br />

|

**Returns:**
float - يُعيد قيمة توقيع Metadata كقيمة float.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


يحوّل إلى DateTime.


**Returns:**
java.util.Date - يُعيد قيمة توقيع Metadata كـ DateTime.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات الخاصية للثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


يحوّل إلى DateTime.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مزود | java.util.Locale | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata

<br />

|

**Returns:**
java.util.Date - يُعيد قيمة توقيع Metadata كـ DateTime.

### toString() {#toString--}
```
public String toString()
```


يحوِّل إلى String باستخدام طريقة ToString() المتجاوزة


**Returns:**
java.lang.String - يُعيد قيمة توقيع Metadata كـ String.

<br />

*** ** * ** ***

يحوِّل خاصية منطقية إلى "True" أو "False". لنوع بيانات آخر سيتم استخدام مزود تنسيق البيانات الافتراضي.

<br />


### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


يحوِّل إلى String باستخدام التنسيق المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تنسيق | java.lang.String | سلسلة تنسيق البيانات. |

<br />

*** ** * ** ***

يحوِّل خاصية منطقية إلى "True" أو "False". سيتم استخدام معلومات الخاصية للثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture

<br />

|

**Returns:**
java.lang.String - يُعيد قيمة توقيع Metadata كـ String.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


يحوِّل إلى String باستخدام التنسيق المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | تنسيق | java.lang.String | سلسلة تنسيق البيانات. |
|
|  | مزود | java.util.Locale | مزود تنسيق البيانات للاستخدام مع عمليات تحويل البيانات. |

<br />

*** ** * ** ***

يحوِّل خاصية منطقية إلى "True" أو "False".

<br />

|

**Returns:**
java.lang.String - يُعيد قيمة توقيع Metadata كـ String.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ كائن توقيع البيانات الوصفية.


**Returns:**
java.lang.Object - يُرجِع نسخة مستنسخة من Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


استنساخ كائن Metadata Signature مع القيمة المعطاة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | java.lang.Object | القيمة للكائن المستنسخ الجديد. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

