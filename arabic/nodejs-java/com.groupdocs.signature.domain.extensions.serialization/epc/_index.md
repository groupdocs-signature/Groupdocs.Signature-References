---
title: "EPC"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل رمز الاستجابة السريعة لمجلس المدفوعات الأوروبي."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

يمثل رمز الاستجابة السريعة لمجلس المدفوعات الأوروبي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EPC()](#EPC--) | ينشئ كائن EPC جديد. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يحصل أو يعيّن اسم المستفيد. |
| [setName(String value)](#setName-java.lang.String-) | يحصل أو يعيّن اسم المستفيد. |
| [getBIC()](#getBIC--) | يحصل أو يعيّن رمز BIC للمستفيد بطول يصل إلى 11 حرفًا. |
| [setBIC(String value)](#setBIC-java.lang.String-) | يحصل أو يعيّن رمز BIC للمستفيد بطول يصل إلى 11 حرفًا. |
| [getIBAN()](#getIBAN--) | يحصل أو يعيّن حساب المستفيد (IBAN). |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | يحصل أو يعيّن حساب المستفيد (IBAN). |
| [getAmount()](#getAmount--) | يحصل أو يعيّن المبلغ. |
| [setAmount(double value)](#setAmount-double-) | يحصل أو يعيّن المبلغ. |
| [getCode()](#getCode--) | يحصل أو يعيّن رمز الأعمال بحد أقصى 4 أحرف. |
| [setCode(String value)](#setCode-java.lang.String-) | يحصل أو يعيّن رمز الأعمال بحد أقصى 4 أحرف. |
| [getReference()](#getReference--) | يحصل أو يعيّن مرجع الدفع (بحد أقصى 35 حرفًا). |
| [setReference(String value)](#setReference-java.lang.String-) | يحصل أو يعيّن مرجع الدفع (بحد أقصى 35 حرفًا). |
| [getRemittance()](#getRemittance--) | يحصل أو يعيّن معلومات التحويل (بحد أقصى 140 حرفًا). |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | يحصل أو يعيّن معلومات التحويل (بحد أقصى 140 حرفًا). |
| [getInformation()](#getInformation--) | يحصل أو يعيّن معلومات التلميح. |
| [setInformation(String value)](#setInformation-java.lang.String-) | يحصل أو يعيّن معلومات التلميح. |
| [getVersion()](#getVersion--) | تنفيذ نسخة EPC / SEPA QR-Code. |
| [setVersion(String value)](#setVersion-java.lang.String-) | تنفيذ نسخة EPC / SEPA QR-Code. |
| [getCharset()](#getCharset--) | تنفيذ مجموعة أحرف EPC / SEPA QR-Code. |
| [setCharset(String value)](#setCharset-java.lang.String-) | تنفيذ مجموعة أحرف EPC / SEPA QR-Code. |
| [getIdentification()](#getIdentification--) | تحديد EPC / SEPA QR-Code. |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | تحديد EPC / SEPA QR-Code. |
| [equals(Object source)](#equals-java.lang.Object-) | يعيد كتابة طريقة Equals لمقارنة خصائص EPC. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
### EPC() {#EPC--}
```
public EPC()
```


ينشئ كائن EPC جديد.

### getName() {#getName--}
```
public final String getName()
```


يحصل أو يعيّن اسم المستفيد. الحد الأقصى للطول هو 70 حرفًا.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


يحصل أو يعيّن اسم المستفيد. الحد الأقصى للطول هو 70 حرفًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


يحصل أو يعيّن رمز BIC للمستفيد بطول يصل إلى 11 حرفًا.

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


يحصل أو يعيّن رمز BIC للمستفيد بطول يصل إلى 11 حرفًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


يحصل أو يعيّن حساب المستفيد (IBAN). يتكون IBAN من ما يصل إلى 34 حرفًا أبجديًا رقميًا.

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


يحصل أو يعيّن حساب المستفيد (IBAN). يتكون IBAN من ما يصل إلى 34 حرفًا أبجديًا رقميًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


يحصل أو يعيّن المبلغ.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


يحصل أو يعيّن المبلغ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


يحصل أو يعيّن رمز الأعمال بحد أقصى 4 أحرف.

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


يحصل أو يعيّن رمز الأعمال بحد أقصى 4 أحرف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


يحصل أو يعيّن مرجع الدفع (بحد أقصى 35 حرفًا). هذا الحقل وحقل معلومات التحويل متعارضان.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


يحصل أو يعيّن مرجع الدفع (بحد أقصى 35 حرفًا). هذا الحقل وحقل معلومات التحويل متعارضان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


يحصل أو يعيّن معلومات التحويل (بحد أقصى 140 حرفًا). هذا الحقل وحقل مرجع الدفع متعارضان.

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


يحصل أو يعيّن معلومات التحويل (بحد أقصى 140 حرفًا). هذا الحقل وحقل مرجع الدفع متعارضان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


يحصل أو يعيّن معلومات التلميح. الحد الأقصى 70 حرفًا.

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


يحصل أو يعيّن معلومات التلميح. الحد الأقصى 70 حرفًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


تنفيذ نسخة EPC / SEPA QR-Code. بشكل افتراضي يتم تعيين هذه القيمة إلى 002.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


تنفيذ نسخة EPC / SEPA QR-Code. بشكل افتراضي يتم تعيين هذه القيمة إلى 002.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


تنفيذ مجموعة أحرف EPC / SEPA QR-Code. بشكل افتراضي يتم تعيين هذه القيمة إلى 1.

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


تنفيذ مجموعة أحرف EPC / SEPA QR-Code. بشكل افتراضي يتم تعيين هذه القيمة إلى 1.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


معرّف EPC / SEPA QR-Code. بشكل افتراضي يتم تعيين هذه القيمة إلى SCT.

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


معرّف EPC / SEPA QR-Code. بشكل افتراضي يتم تعيين هذه القيمة إلى SCT.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


يعيد كتابة طريقة Equals لمقارنة خصائص EPC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المصدر | java.lang.Object | كائن EPC للمقارنة معه. |

**Returns:**
منطقي - يُرجع true إذا كان كائن العنوان الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا المثيل.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int - رمز تجزئة البريد الإلكتروني
