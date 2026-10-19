---
title: "ImageMetadataSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع بيانات تعريف الصورة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات تعريف الصورة.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | إنشاء توقيع بيانات تعريف الصورة مع المعرف والقيمة |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getId()](#getId--) | معرف توقيع بيانات تعريف الصورة. |
|
|  | [setId(int value)](#setId-int-) | معرف توقيع بيانات تعريف الصورة. |
|
|  | [getSize()](#getSize--) | قيمة للقراءة فقط للحصول على حجم قيمة البيانات الوصفية |
|
|  | [setSize(int value)](#setSize-int-) | قيمة للقراءة فقط للحصول على حجم قيمة البيانات الوصفية |
|
|  | [getDescription()](#getDescription--) | قيمة للقراءة فقط للحصول على وصف توقيع بيانات تعريف الصورة القياسي |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ كائن توقيع البيانات الوصفية. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ نسخة من توقيع بيانات تعريف الصورة مع القيمة المعطاة. |
|
|  | [toBoolean()](#toBoolean--) | يحوّل إلى قيمة منطقية. |
|
|  | [toInteger()](#toInteger--) | يحوّل إلى عدد صحيح. |
|
|  | [toLong()](#toLong--) | تحويل إلى long. |
|
|  | [toSingle()](#toSingle--) | يحوّل إلى float. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | يحوّل إلى float. |
|
|  | [toDouble()](#toDouble--) | يحوّل إلى Double. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | يحوّل إلى Double. |
|
|  | [toDecimal()](#toDecimal--) | تحويل إلى Decimal. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | تحويل إلى Decimal. |
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
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


إنشاء توقيع بيانات تعريف الصورة مع المعرف والقيمة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المعرّف | int | معرّف فريد لاسم توقيع البيانات الوصفية للصورة. راجع المراجع لمواصفات علامات Exif للقيم المحتملة للمعرّف |
|
|  | قيمة | java.lang.Object | قيمة البيانات الوصفية |
|

### getId() {#getId--}
```
public final int getId()
```


معرف توقيع بيانات تعريف الصورة.
انظر فئة [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) التي تحتوي على توقيع قياسي مع قيمة معرف محددة مسبقًا.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


معرف توقيع بيانات تعريف الصورة.
انظر فئة [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) التي تحتوي على توقيع قياسي مع قيمة معرف محددة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


قيمة للقراءة فقط للحصول على حجم قيمة البيانات الوصفية


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


قيمة للقراءة فقط للحصول على حجم قيمة البيانات الوصفية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


قيمة للقراءة فقط للحصول على وصف توقيع بيانات تعريف الصورة القياسي


**Returns:**
java.lang.String
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


استنساخ نسخة من توقيع بيانات تعريف الصورة مع القيمة المعطاة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | java.lang.Object | القيمة للكائن المستنسخ الجديد. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

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


### toLong() {#toLong--}
```
public final long toLong()
```


تحويل إلى long.


**Returns:**
long - إرجاع قيمة توقيع البيانات الوصفية كـ long.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


يحوّل إلى float.


**Returns:**
float - إرجاع قيمة توقيع بيانات تعريف الصورة كـ float.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات الخاصية للثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
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

### toDouble() {#toDouble--}
```
public double toDouble()
```


يحوّل إلى Double.


**Returns:**
double - إرجاع قيمة توقيع بيانات تعريف الصورة كـ Double.

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

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


تحويل إلى Decimal.


**Returns:**
java.math.BigDecimal - إرجاع قيمة توقيع بيانات تعريف الصورة كـ Decimal.

<br />

*** ** * ** ***

يرمي استثناءً إذا تعذّر تحويل قيمة Metadata. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات الخاصية للثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


تحويل إلى Decimal.


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
java.math.BigDecimal - إرجاع قيمة توقيع البيانات الوصفية كـ Decimal.

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

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object |  |

