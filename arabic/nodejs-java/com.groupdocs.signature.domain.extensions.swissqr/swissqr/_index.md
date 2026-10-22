---
title: "SwissQR"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "فئة لتشفير وفك تشفير النص المضمن في رمز SwissQR."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

فئة لتشفير وفك تشفير النص المضمن في رمز SwissQR.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SwissQR()](#SwissQR--) | ينشئ مثلاً من SwissQR. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getAmount()](#getAmount--) | يحصل أو يعيّن مبلغ الدفع. |
| [setAmount(double value)](#setAmount-double-) | يحصل أو يعيّن مبلغ الدفع. |
| [getCurrency()](#getCurrency--) | يحصل أو يعيّن عملة الدفع. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | يحصل أو يعيّن عملة الدفع. |
| [getAccount()](#getAccount--) | يحصل أو يعيّن رقم حساب الدائن. |
| [setAccount(String value)](#setAccount-java.lang.String-) | يحصل أو يعيّن رقم حساب الدائن. |
| [getCreditor()](#getCreditor--) | يحصل أو يعيّن عنوان الدائن. |
| [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | يحصل أو يعيّن عنوان الدائن. |
| [getReference()](#getReference--) | يحصل أو يعيّن مرجع دفع الدائن. |
| [setReference(String value)](#setReference-java.lang.String-) | يحصل أو يعيّن مرجع دفع الدائن. |
| [getDebtor()](#getDebtor--) | يحصل أو يعيّن عنوان المدين. |
| [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | يحصل أو يعيّن عنوان المدين. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | يحصل أو يعيّن الرسالة غير المهيكلة الإضافية. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | يحصل أو يعيّن الرسالة غير المهيكلة الإضافية. |
| [getBillInformation()](#getBillInformation--) | يحصل أو يعيّن معلومات الفاتورة المهيكلة الإضافية. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | يحصل أو يعيّن معلومات الفاتورة المهيكلة الإضافية. |
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


ينشئ مثلاً من SwissQR.

### getAmount() {#getAmount--}
```
public final double getAmount()
```


يحصل أو يعيّن مبلغ الدفع. القيم الصالحة بين 0.01 و 999,999,999.99.

القيمة: مبلغ الدفع.

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


يحصل أو يعيّن مبلغ الدفع. القيم الصالحة بين 0.01 و 999,999,999.99.

القيمة: مبلغ الدفع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


يسترجع أو يعيّن عملة الدفع. القيم الصالحة هي "CHF" و "EUR".

القيمة: عملة الدفع.

**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


يسترجع أو يعيّن عملة الدفع. القيم الصالحة هي "CHF" و "EUR".

القيمة: عملة الدفع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


يسترجع أو يعيّن رقم حساب الدائن. يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. يُسمح بالمسافات في رقم الحساب.

القيمة: رقم حساب الدائن.

**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


يسترجع أو يعيّن رقم حساب الدائن. يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. يُسمح بالمسافات في رقم الحساب.

القيمة: رقم حساب الدائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


يحصل أو يعيّن عنوان الدائن.

القيمة: عنوان الدائن.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


يحصل أو يعيّن عنوان الدائن.

القيمة: عنوان الدائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


يسترجع أو يعيّن مرجع دفع الدائن. المرجع إلزامي لـ IBANs SwissQR، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx. إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا للمعيار ISO 11649 ("RFxxxx"). كلاهما قد يحتوي على مسافات للتنسيق.

القيمة: مرجع دفع الدائن.

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


يسترجع أو يعيّن مرجع دفع الدائن. المرجع إلزامي لـ IBANs SwissQR، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx. إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا للمعيار ISO 11649 ("RFxxxx"). كلاهما قد يحتوي على مسافات للتنسيق.

القيمة: مرجع دفع الدائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


يسترجع أو يعيّن عنوان المدين. المدين اختياري. إذا تم حذفه، فإن تعيين هذا الحقل إلى null أو تعيين عنوان يحتوي على جميع القيم null أو فارغة يعتبر مقبولًا.

القيمة: عنوان المدين.

**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


يسترجع أو يعيّن عنوان المدين. المدين اختياري. إذا تم حذفه، فإن تعيين هذا الحقل إلى null أو تعيين عنوان يحتوي على جميع القيم null أو فارغة يعتبر مقبولًا.

القيمة: عنوان المدين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


يحصل أو يعيّن الرسالة غير المهيكلة الإضافية.

القيمة: الرسالة غير المهيكلة.

**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


يحصل أو يعيّن الرسالة غير المهيكلة الإضافية.

القيمة: الرسالة غير المهيكلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


يحصل أو يعيّن معلومات الفاتورة المهيكلة الإضافية.

القيمة: معلومات الفاتورة المهيكلة.

**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


يحصل أو يعيّن معلومات الفاتورة المهيكلة الإضافية.

القيمة: معلومات الفاتورة المهيكلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

