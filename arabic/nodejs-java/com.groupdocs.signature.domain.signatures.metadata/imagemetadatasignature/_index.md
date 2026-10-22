---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع بيانات وصفية للصورة."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات وصفية للصورة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | ينشئ Image Metadata Signature مع المعرف والقيمة |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getId()](#getId--) | معرف Image Metadata signature. |
| [setId(int value)](#setId-int-) | معرف Image Metadata signature. |
| [getSize()](#getSize--) | قيمة للقراءة فقط للحصول على حجم قيمة Metadata |
| [setSize(int value)](#setSize-int-) | قيمة للقراءة فقط للحصول على حجم قيمة Metadata |
| [getDescription()](#getDescription--) | قيمة للقراءة فقط للحصول على الوصف لتوقيع Image Metadata القياسي |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن توقيع Metadata. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ كائن Image Metadata Signature مع القيمة المعطاة. |
| [toBoolean()](#toBoolean--) | يحول إلى قيمة منطقية. |
| [toInteger()](#toInteger--) | يحول إلى عدد صحيح. |
| [toLong()](#toLong--) | يحول إلى long. |
| [toSingle()](#toSingle--) | يحول إلى عدد عشري. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | يحول إلى عدد عشري. |
| [toDouble()](#toDouble--) | يحول إلى قيمة مزدوجة. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | يحول إلى قيمة مزدوجة. |
| [toDecimal()](#toDecimal--) | يحول إلى Decimal. |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | يحول إلى Decimal. |
| [toDateTime()](#toDateTime--) | يحول إلى تاريخ ووقت. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | يحول إلى تاريخ ووقت. |
| [toString()](#toString--) | يحول إلى سلسلة باستخدام طريقة ToString() المتجاوزة |
| [toString(String format)](#toString-java.lang.String-) | يحول إلى سلسلة بالتنسيق المحدد |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | يحول إلى سلسلة بالتنسيق المحدد |
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


ينشئ Image Metadata Signature مع المعرف والقيمة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المعرّف | int | معرّف فريد لاسم توقيع بيانات الصورة الوصفية. راجع المراجع لمواصفات علامات Exif للحصول على القيم المحتملة للمعرّف. |
| قيمة | java.lang.Object | قيمة البيانات الوصفية |

### getId() {#getId--}
```
public final int getId()
```


معرف Image Metadata signature. راجع فئة [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) التي تحتوي على توقيع قياسي بمعرف محدد مسبقًا.

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


معرف Image Metadata signature. راجع فئة [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) التي تحتوي على توقيع قياسي بمعرف محدد مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


قيمة للقراءة فقط للحصول على حجم قيمة Metadata

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


قيمة للقراءة فقط للحصول على حجم قيمة Metadata

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


قيمة للقراءة فقط للحصول على الوصف لتوقيع Image Metadata القياسي

**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| توقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |

**Returns:**
boolean - يُرجِع true إذا كان كائن التوقيع الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا الكائن.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int - رمز التجزئة للتوقيع
### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ كائن توقيع Metadata.

**Returns:**
java.lang.Object - يعيد نسخة مستنسخة من كائن توقيع Metadata
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


استنساخ كائن Image Metadata Signature مع القيمة المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object | قيمة للكائن المستنسخ الجديد. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


يحول إلى قيمة منطقية.

**Returns:**
boolean - يُعيد قيمة توقيع البيانات الوصفية كقيمة منطقية.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.
### toInteger() {#toInteger--}
```
public int toInteger()
```


يحول إلى عدد صحيح.

**Returns:**
int - يُعيد قيمة توقيع البيانات الوصفية كعدد صحيح.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.
### toLong() {#toLong--}
```
public final long toLong()
```


يحول إلى long.

**Returns:**
long - يُرجِع قيمة Metadata Signature كـ long.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية.
### toSingle() {#toSingle--}
```
public final float toSingle()
```


يحول إلى عدد عشري.

**Returns:**
float - يُرجِع قيمة Image Metadata Signature كـ float.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


يحول إلى عدد عشري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المزود | java.util.Locale | مزود تنسيق البيانات لاستخدامه مع عمليات تحويل البيانات. |

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية |

**Returns:**
float - يُعيد قيمة توقيع البيانات الوصفية كقيمة عائمة.
### toDouble() {#toDouble--}
```
public double toDouble()
```


يحول إلى قيمة مزدوجة.

**Returns:**
double - يُرجِع قيمة Image Metadata Signature كـ Double.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


يحول إلى قيمة مزدوجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المزود | java.util.Locale | مزود تنسيق البيانات لاستخدامه مع عمليات تحويل البيانات. |

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية |

**Returns:**
double - يُعيد قيمة توقيع البيانات الوصفية كـ Double.
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


يحول إلى Decimal.

**Returns:**
java.math.BigDecimal - يُرجِع قيمة Image Metadata Signature كـ Decimal.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


يحول إلى Decimal.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المزود | java.util.Locale | مزود تنسيق البيانات لاستخدامه مع عمليات تحويل البيانات. |

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية |

**Returns:**
java.math.BigDecimal - يُرجِع قيمة Metadata Signature كـ Decimal.
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


يحول إلى تاريخ ووقت.

**Returns:**
java.util.Date - يُعيد قيمة توقيع البيانات الوصفية كـ DateTime.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


يحول إلى تاريخ ووقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المزود | java.util.Locale | مزود تنسيق البيانات لاستخدامه مع عمليات تحويل البيانات. |

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية |

**Returns:**
java.util.Date - يُعيد قيمة توقيع البيانات الوصفية كـ DateTime.
### toString() {#toString--}
```
public String toString()
```


يحول إلى سلسلة باستخدام طريقة ToString() المتجاوزة

**Returns:**
java.lang.String - يُعيد قيمة توقيع البيانات الوصفية كـ String.
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


يحول إلى سلسلة بالتنسيق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التنسيق | java.lang.String | سلسلة تنسيق البيانات. |

--------------------

يحوّل خاصية منطقية إلى "True" أو "False". سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture  |

**Returns:**
java.lang.String - يُعيد قيمة توقيع البيانات الوصفية كـ String.
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


يحول إلى سلسلة بالتنسيق المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التنسيق | java.lang.String | سلسلة تنسيق البيانات. |
|  | المزود | java.util.Locale | مزود تنسيق البيانات لاستخدامه مع عمليات تحويل البيانات. |

--------------------

يحوّل خاصية منطقية إلى "True" أو "False". |

**Returns:**
java.lang.String - يُعيد قيمة توقيع البيانات الوصفية كـ String.
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

