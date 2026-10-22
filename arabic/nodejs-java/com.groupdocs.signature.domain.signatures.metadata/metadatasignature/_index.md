---
title: "MetadataSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع البيانات الوصفية."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

يحتوي على خصائص توقيع البيانات الوصفية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يحدد اسم بيانات التعريف الفريد. |
| [setName(String value)](#setName-java.lang.String-) | يحدد اسم بيانات التعريف الفريد. |
| [getValue()](#getValue--) | يحدد كائن بيانات التعريف. |
| [setValue(Object value)](#setValue-java.lang.Object-) | يحدد كائن بيانات التعريف. |
| [getType()](#getType--) | يحدد نوع قيمة بيانات التعريف. |
| [setType(int value)](#setType-int-) | يحدد نوع قيمة بيانات التعريف. |
| [getDataEncryption()](#getDataEncryption--) | يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص Value للتوقيع. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص Value للتوقيع. |
| [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | احصل على الكائن من قيمة توقيع البيانات التعريفية أثناء عملية فك التسلسل. |
| [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | احصل على الكائن من نص توقيع البيانات التعريفية أثناء عملية فك التسلسل. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [toBoolean()](#toBoolean--) | يحول إلى قيمة منطقية. |
| [toInteger()](#toInteger--) | يحول إلى عدد صحيح. |
| [toDouble()](#toDouble--) | يحول إلى قيمة مزدوجة. |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | يحول إلى قيمة مزدوجة. |
| [toSingle()](#toSingle--) | يحول إلى عدد عشري. |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | يحول إلى عدد عشري. |
| [toDateTime()](#toDateTime--) | يحول إلى تاريخ ووقت. |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | يحول إلى تاريخ ووقت. |
| [toString()](#toString--) | يحول إلى سلسلة باستخدام طريقة ToString() المتجاوزة |
| [toString(String format)](#toString-java.lang.String-) | يحول إلى سلسلة بالتنسيق المحدد |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | يحول إلى سلسلة بالتنسيق المحدد |
| [deepClone()](#deepClone--) | استنساخ كائن توقيع Metadata. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ نسخة من توقيع البيانات التعريفية مع القيمة المحددة. |
### getName() {#getName--}
```
public final String getName()
```


يحدد اسم بيانات التعريف الفريد.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحدد اسم بيانات التعريف الفريد.

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


يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص Value للتوقيع.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


يحصل أو يعيّن تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص Value للتوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


احصل على الكائن من قيمة توقيع البيانات التعريفية أثناء عملية فك التسلسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - نسخة من كائن T

T : نوع الكائن لفك التسلسل من قيمة البيانات الوصفية
### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


احصل على الكائن من نص توقيع البيانات التعريفية أثناء عملية فك التسلسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | تعيين تنفيذ تشفير البيانات المخصص |

T : نوع الكائن لفك التسلسل من قيمة البيانات الوصفية |

**Returns:**
T -
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
### toDouble() {#toDouble--}
```
public double toDouble()
```


يحول إلى قيمة مزدوجة.

**Returns:**
double - يُعيد قيمة توقيع البيانات الوصفية كـ Double.

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
### toSingle() {#toSingle--}
```
public float toSingle()
```


يحول إلى عدد عشري.

**Returns:**
float - يُعيد قيمة توقيع البيانات الوصفية كقيمة عائمة.

--------------------

يرمي استثناءً إذا تعذر تحويل قيمة البيانات الوصفية. إذا كانت القيمة الأصلية نصية، سيتم استخدام معلومات خاصية الثقافة الافتراضية من خصائص SignatureSettings  SignatureSettings.DefaultCulture ()
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

--------------------

يحوّل خاصية منطقية إلى "True" أو "False". بالنسبة لنوع بيانات آخر سيتم استخدام مزود تنسيق البيانات الافتراضي.
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


استنساخ نسخة من توقيع البيانات التعريفية مع القيمة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object | قيمة للكائن المستنسخ الجديد. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.
