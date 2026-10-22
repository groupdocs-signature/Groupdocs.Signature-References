---
title: "DigitalVBA"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل التوقيع الرقمي لمشاريع VBA في جداول البيانات."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

يمثل توقيعًا رقميًا لمشروعات VBA في جداول البيانات. يوفر القدرة على توقيع مشروع VBA في صيغ مستندات جداول البيانات المحددة مثل Xlsm أو Xltm. إذا تمت إضافة عدة امتدادات DigitalVBA إلى DigitalSignOptions.Extensions فإن الأول فقط يُستخدم في توقيع المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | يُنشئ مثيلًا جديدًا لفئة DigitalVBA باستخدام ملف الشهادة. |
| [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | يُنشئ مثيلًا جديدًا لفئة DigitalVBA باستخدام تدفق الشهادة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getComments()](#getComments--) | يحصل أو يعيّن تعليقات التوقيع. |
| [setComments(String value)](#setComments-java.lang.String-) | يحصل أو يعيّن تعليقات التوقيع. |
| [getPassword()](#getPassword--) | يحصل أو يضبط كلمة مرور الشهادة الرقمية. |
| [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يضبط كلمة مرور الشهادة الرقمية. |
| [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | يحصل أو يعيّن إعداد توقيع مشروع VBA فقط. |
| [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | يحصل أو يعيّن إعداد توقيع مشروع VBA فقط. |
| [getCertificateFilePath()](#getCertificateFilePath--) | يحصل على مسار ملف الشهادة الرقمية. |
| [getCertificateStream()](#getCertificateStream--) | يحصل على تدفق الشهادة الرقمية. |
| [release()](#release--) | طريقة تجاوز لتنظيف الموارد بعد التوقيع. |
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


يُنشئ مثيلًا جديدًا لفئة DigitalVBA باستخدام ملف الشهادة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateFilePath | java.lang.String | مسار ملف الشهادة الرقمية |
| كلمة المرور | java.lang.String | كلمة مرور الشهادة الرقمية |

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


يُنشئ مثيلًا جديدًا لفئة DigitalVBA باستخدام تدفق الشهادة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| certificateStream | java.io.InputStream | دفق الشهادة الرقمية |
| كلمة المرور | java.lang.String | كلمة مرور الشهادة الرقمية |

### getComments() {#getComments--}
```
public final String getComments()
```


يحصل أو يعيّن تعليقات التوقيع.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


يحصل أو يعيّن تعليقات التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل أو يضبط كلمة مرور الشهادة الرقمية.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل أو يضبط كلمة مرور الشهادة الرقمية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


يحصل أو يعيّن إعداد توقيع مشروع VBA فقط. إذا تم تعيينه إلى true، فلن يتم توقيع مستند SpreadSheet، لكن سيتم توقيع مشروع VBA.

**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


يحصل أو يعيّن إعداد توقيع مشروع VBA فقط. إذا تم تعيينه إلى true، فلن يتم توقيع مستند SpreadSheet، لكن سيتم توقيع مشروع VBA.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


يحصل على مسار ملف الشهادة الرقمية. تُستخدم هذه الخاصية فقط إذا لم يتم تحديد CertificateStream.

**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


يحصل على تدفق الشهادة الرقمية. إذا تم تحديد هذه الخاصية، فستُستَخدم دائمًا بدلاً من CertificateFilePath.

**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


طريقة تجاوز لتنظيف الموارد بعد التوقيع.

