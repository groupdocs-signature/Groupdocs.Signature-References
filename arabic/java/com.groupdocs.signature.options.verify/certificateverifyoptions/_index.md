---
title: "CertificateVerifyOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحافظ على خيارات التحقق من مستندات الشهادة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

يحافظ على خيارات التحقق من مستندات الشهادة.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | ينشئ مثلاً جديداً من TextVerifyOptions بالقيم الافتراضية. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | ينشئ مثيلاً جديداً من CertificateVerifyOptions مع الموضوع المراد التحقق منه. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | حدد مصدر الشهادة إذا كان يجب التحقق منه. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | حدد مصدر الشهادة إذا كان يجب التحقق منه. |
|
|  | [getSerialNumber()](#getSerialNumber--) | حدد الرقم التسلسلي للشهادة إذا كان يجب التحقق منه. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | حدد الرقم التسلسلي للشهادة إذا كان يجب التحقق منه. |
|
|  | [getSubject()](#getSubject--) | حدد موضوع الشهادة إذا كان يجب التحقق منه. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | حدد موضوع الشهادة إذا كان يجب التحقق منه. |
|
|  | [getThumbprint()](#getThumbprint--) | حدد بصمة الشهادة إذا كان يجب التحقق منها. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | حدد بصمة الشهادة إذا كان يجب التحقق منها. |
|
|  | [getMatchType()](#getMatchType--) | يحصل أو يعيّن التحقق من نوع مطابقة النص. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | يحصل أو يعيّن التحقق من نوع مطابقة النص. |
|
|  | [getExpired()](#getExpired--) | يشير إلى ما إذا كان تاريخ انتهاء الشهادة بسبب نتيجة التحقق. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | يشير إلى ما إذا كان تاريخ انتهاء الشهادة بسبب نتيجة التحقق. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | احصل أو اضبط إذا كان عملية التحقق يجب أن توفر تحقق سلسلة X.509 باستخدام سياسة التحقق الأساسية. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | احصل أو اضبط إذا كان عملية التحقق يجب أن توفر تحقق سلسلة X.509 باستخدام سياسة التحقق الأساسية. |
|
|  | [toString()](#toString--) | يتجاوز التحويل إلى string. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


ينشئ مثلاً جديداً من TextVerifyOptions بالقيم الافتراضية.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


ينشئ مثيلاً جديداً من CertificateVerifyOptions مع الموضوع المراد التحقق منه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الموضوع | java.lang.String | الموضوع المراد التحقق منه |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


حدد مصدر الشهادة إذا كان يجب التحقق منه.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


حدد مصدر الشهادة إذا كان يجب التحقق منه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


حدد الرقم التسلسلي للشهادة إذا كان يجب التحقق منه.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


حدد الرقم التسلسلي للشهادة إذا كان يجب التحقق منه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


حدد موضوع الشهادة إذا كان يجب التحقق منه.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


حدد موضوع الشهادة إذا كان يجب التحقق منه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


حدد بصمة الشهادة إذا كان يجب التحقق منها.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


حدد بصمة الشهادة إذا كان يجب التحقق منها.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


يحصل أو يعيّن التحقق من نوع مطابقة النص.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


يحصل أو يعيّن التحقق من نوع مطابقة النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


يشير إلى ما إذا كان تاريخ انتهاء الشهادة بسبب نتيجة التحقق.
الخاصية للقراءة فقط.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


يشير إلى ما إذا كان تاريخ انتهاء الشهادة بسبب نتيجة التحقق.
الخاصية للقراءة فقط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


احصل أو اضبط إذا كان عملية التحقق يجب أن توفر تحقق سلسلة X.509 باستخدام سياسة التحقق الأساسية.
بشكل افتراضي هذه القيمة صحيحة.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


احصل أو اضبط إذا كان عملية التحقق يجب أن توفر تحقق سلسلة X.509 باستخدام سياسة التحقق الأساسية.
بشكل افتراضي هذه القيمة صحيحة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى string.


**Returns:**
java.lang.String -
