---
title: "TextVerifyOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحافظ على خيارات التحقق من توقيع النص للمستند."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

يحافظ على خيارات التحقق من توقيع النص للمستند.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | ينشئ مثلاً جديداً من TextVerifyOptions بالقيم الافتراضية. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | ينشئ مثلاً جديداً من TextVerifyOptions بنص التحقق. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | ينشئ مثلاً جديداً من TextVerifyOptions بخصية Text للتحقق وتنفيذ التوقيع. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getText()](#getText--) | حدد نص التوقيع إذا كان يجب التحقق منه. |
|
|  | [setText(String value)](#setText-java.lang.String-) | حدد نص التوقيع إذا كان يجب التحقق منه. |
|
|  | [getMatchType()](#getMatchType--) | يحصل أو يعيّن التحقق من نوع مطابقة النص. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | يحصل أو يعيّن التحقق من نوع مطابقة النص. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | نوع التوقيع الذي سيتم التحقق منه. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | نوع التوقيع الذي سيتم التحقق منه. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | يحصل أو يعيّن عنوان حقل النموذج للتحقق منه. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | يحصل أو يعيّن عنوان حقل النموذج للتحقق منه. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | يحصل أو يضبط نوع حقل النموذج للتحقق منه. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | يحصل أو يضبط نوع حقل النموذج للتحقق منه. |
|
|  | [getSignatureID()](#getSignatureID--) | حدد معرف توقيع النص أكبر من الصفر إذا كان يجب التحقق منه. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | حدد معرف توقيع النص أكبر من الصفر إذا كان يجب التحقق منه. |
|
|  | [toString()](#toString--) | يتجاوز التحويل إلى string. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


ينشئ مثلاً جديداً من TextVerifyOptions بالقيم الافتراضية.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


ينشئ مثلاً جديداً من TextVerifyOptions بنص التحقق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | النص المراد التحقق منه |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


ينشئ مثلاً جديداً من TextVerifyOptions بخصية Text للتحقق وتنفيذ التوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | نص | java.lang.String | النص المراد التحقق منه. |
|
|  | تنفيذ | int | نوع تنفيذ التوقيع. |
|

### getText() {#getText--}
```
public final String getText()
```


حدد نص التوقيع إذا كان يجب التحقق منه.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


حدد نص التوقيع إذا كان يجب التحقق منه.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


نوع التوقيع الذي سيتم التحقق منه.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


نوع التوقيع الذي سيتم التحقق منه.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


يحصل أو يعيّن عنوان حقل النموذج للتحقق منه.
إذا تم تعيين هذا الخاصية، سيُعثر على النص فقط في حقول النموذج النصية.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


يحصل أو يعيّن عنوان حقل النموذج للتحقق منه.
إذا تم تعيين هذا الخاصية، سيُعثر على النص فقط في حقول النموذج النصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


يحصل أو يضبط نوع حقل النموذج للتحقق منه.
إذا تم تعيين هذا الخاصية، سيُعثر على النص فقط في حقول النموذج النصية.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


يحصل أو يضبط نوع حقل النموذج للتحقق منه.
إذا تم تعيين هذا الخاصية، سيُعثر على النص فقط في حقول النموذج النصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


حدد معرف توقيع النص أكبر من الصفر إذا كان يجب التحقق منه. هذه الخاصية مدعومة فقط لمستندات PDF


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


حدد معرف توقيع النص أكبر من الصفر إذا كان يجب التحقق منه. هذه الخاصية مدعومة فقط لمستندات PDF


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يتجاوز التحويل إلى string.


**Returns:**
java.lang.String -
