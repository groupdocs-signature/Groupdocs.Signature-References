---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحافظ على خيارات التحقق من التوقيع الرقمي للمستند."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

يحافظ على خيارات التحقق من التوقيع الرقمي للمستند.

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | ينشئ خيار التحقق الرقمي باستخدام القيم الافتراضية. |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | ينشئ خيار التحقق الرقمي باستخدام معرف شهادة رقمية محدد. |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | ينشئ خيار التحقق الرقمي باستخدام تدفق شهادة محدد. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCertificate()](#getCertificate--) | احصل على شهادة X509Certificate2 من معرف الشهادة أو التدفق. |
| [getPassword()](#getPassword--) | كلمة مرور الشهادة الرقمية إذا كانت مطلوبة. |
| [setPassword(String value)](#setPassword-java.lang.String-) | كلمة مرور الشهادة الرقمية إذا كانت مطلوبة. |
| [getCertificateFilePath()](#getCertificateFilePath--) | معرف الملف للشهادة الرقمية. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | معرف الملف للشهادة الرقمية. |
| [getCertificateStream()](#getCertificateStream--) | تدفق الشهادة الرقمية. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | تدفق الشهادة الرقمية. |
| [getComments()](#getComments--) | تعليقات التوقيع الرقمي للتحقق. |
| [setComments(String value)](#setComments-java.lang.String-) | تعليقات التوقيع الرقمي للتحقق. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. |
| [getReason()](#getReason--) | سبب التوقيع الرقمي للتحقق. |
| [setReason(String value)](#setReason-java.lang.String-) | سبب التوقيع الرقمي للتحقق. |
| [getContact()](#getContact--) | جهة اتصال التوقيع للتحقق. |
| [setContact(String value)](#setContact-java.lang.String-) | جهة اتصال التوقيع للتحقق. |
| [getLocation()](#getLocation--) | موقع التوقيع للتحقق. |
| [setLocation(String value)](#setLocation-java.lang.String-) | موقع التوقيع للتحقق. |
| [getSubjectName()](#getSubjectName--) | الاسم المميز للموضوع في الشهادة للتحقق. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | الاسم المميز للموضوع في الشهادة للتحقق. |
| [getIssuerName()](#getIssuerName--) | اسم الجهة المصدرة للشهادة للتحقق. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | اسم الجهة المصدرة للشهادة للتحقق. |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


ينشئ خيار التحقق الرقمي باستخدام القيم الافتراضية.

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


ينشئ خيار التحقق الرقمي باستخدام معرف شهادة رقمية محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateGuid | java.lang.String | مسار الملف إلى الشهادة الرقمية. |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


ينشئ خيار التحقق الرقمي باستخدام تدفق شهادة محدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateStream | java.io.InputStream | تدفق الشهادة. |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


احصل على شهادة X509Certificate2 من معرف الشهادة أو التدفق.

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة مرور الشهادة الرقمية إذا كانت مطلوبة.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


كلمة مرور الشهادة الرقمية إذا كانت مطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


معرف الملف للشهادة الرقمية.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


معرف الملف للشهادة الرقمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


تدفق الشهادة الرقمية.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


تدفق الشهادة الرقمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


تعليقات التوقيع الرقمي للتحقق.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


تعليقات التوقيع الرقمي للتحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. سيتم تجاهل القيمة القابلة للعدم.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. سيتم تجاهل القيمة القابلة للعدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. سيتم تجاهل القيمة القابلة للعدم.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


نطاق التاريخ والوقت للتوقيع الرقمي للتحقق. سيتم تجاهل القيمة القابلة للعدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


سبب التوقيع الرقمي للتحقق.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


سبب التوقيع الرقمي للتحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


جهة اتصال التوقيع للتحقق.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


جهة اتصال التوقيع للتحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


موقع التوقيع للتحقق.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


موقع التوقيع للتحقق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


الاسم المميز للموضوع في الشهادة للتحقق. القيمة حساسة لحالة الأحرف. إذا تم تعيين هذه الخاصية، سيتحقق التحقق مما إذا كان اسم موضوع التوقيع يحتوي على القيمة الممررة أو يساها.

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


الاسم المميز للموضوع في الشهادة للتحقق. القيمة حساسة لحالة الأحرف. إذا تم تعيين هذه الخاصية، سيتحقق التحقق مما إذا كان اسم موضوع التوقيع يحتوي على القيمة الممررة أو يساها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


اسم الجهة المصدرة للشهادة للتحقق. القيمة حساسة لحالة الأحرف. إذا تم تعيين هذه الخاصية، سيتحقق التحقق مما إذا كان اسم الجهة المصدرة للتوقيع يحتوي على القيمة الممررة أو يساها.

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


اسم الجهة المصدرة للشهادة للتحقق. القيمة حساسة لحالة الأحرف. إذا تم تعيين هذه الخاصية، سيتحقق التحقق مما إذا كان اسم الجهة المصدرة للتوقيع يحتوي على القيمة الممررة أو يساها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

