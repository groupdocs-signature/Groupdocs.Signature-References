---
title: "SignatureSettings"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحدد الإعدادات لتخصيص السلوك."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

يحدد الإعدادات لتخصيص سلوك [التوقيع](../../com.groupdocs.signature/signature).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SignatureSettings()](#SignatureSettings--) | ينشئ مثيلًا افتراضيًا من SignatureSettings بالقيم الافتراضية. |
| [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | ينشئ مثيلًا افتراضيًا من SignatureSettings باستخدام تنفيذ Logger. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDefaultCulture()](#getDefaultCulture--) | يحصل أو يعيّن الثقافة الافتراضية التي ستُستخدم أثناء معالجة المستند. |
| [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | يحصل أو يعيّن الثقافة الافتراضية التي ستُستخدم أثناء معالجة المستند. |
| [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | يحصل أو يعيّن العلامة التي تشمل التوقيعات المحذوفة في نتيجة معلومات المستند. |
| [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | يحصل أو يعيّن العلامة التي تشمل التوقيعات المحذوفة في نتيجة معلومات المستند. |
| [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | يحصل أو يعيّن العلامة لإعادة حفظ المستند المصدر عندما لا تحتوي طريقة Update على توقيعات لتحديثها. |
| [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | يحصل أو يعيّن العلامة لإعادة حفظ المستند المصدر عندما لا تحتوي طريقة Update على توقيعات لتحديثها. |
| [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | يحصل أو يعيّن العلامة لإعادة حفظ المستند المصدر عندما لا تحتوي طريقة Delete على توقيعات متأثرة لإزالتها. |
| [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | يحصل أو يعيّن العلامة لإعادة حفظ المستند المصدر عندما لا تحتوي طريقة Delete على توقيعات متأثرة لإزالتها. |
| [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | يحصل أو يعيّن العلامة لتضمين توقيعات بيانات التعريف المدمجة القياسية في قائمة Metadata مثل المؤلف، المالك، تاريخ إنشاء المستند، تاريخ التعديل، إلخ. |
| [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | يحصل أو يعيّن العلامة لتضمين توقيعات بيانات التعريف المدمجة القياسية في قائمة Metadata مثل المؤلف، المالك، تاريخ إنشاء المستند، تاريخ التعديل، إلخ. |
| [getLogger()](#getLogger--) | تنفيذ المسجل المستخدم للتسجيل (الأخطاء، التحذيرات، المتتبعات). |
| [getLogLevel()](#getLogLevel--) | مستوى التسجيل لتقييد الرسائل (الكل، المتتبعات، التحذيرات، الأخطاء). |
| [setLogLevel(int value)](#setLogLevel-int-) | مستوى التسجيل لتقييد الرسائل (الكل، المتتبعات، التحذيرات، الأخطاء). |
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


ينشئ مثيلًا افتراضيًا من SignatureSettings بالقيم الافتراضية.

### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


ينشئ مثيلًا افتراضيًا من SignatureSettings باستخدام تنفيذ Logger.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


يحصل أو يضبط الثقافة الافتراضية المستخدمة أثناء معالجة المستند. القيمة الافتراضية هي "en-US".

**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


يحصل أو يضبط الثقافة الافتراضية المستخدمة أثناء معالجة المستند. القيمة الافتراضية هي "en-US".

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


يحصل أو يضبط العلامة التي تشمل التوقيعات المحذوفة في نتيجة معلومات المستند. كل توقيع [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) لديه علامة Deleted  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) لاكتشاف ما إذا تم حذفه.

**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


يحصل أو يضبط العلامة التي تشمل التوقيعات المحذوفة في نتيجة معلومات المستند. كل توقيع [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) لديه علامة Deleted  BaseSignature.Deleted ([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature\#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setDeleted-boolean-)) لاكتشاف ما إذا تم حذفه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


يحصل أو يضبط العلامة لإعادة حفظ المستند الأصلي عندما لا تحتوي طريقة Update على توقيعات للتحديث. إذا تم ضبط هذه العلامة على true (افتراضيًا) سيتم حفظ المستند مع سجل عملية التاريخ المقابل (التاريخ ونوع العملية) حتى إذا لم تحتوي طريقة Update على توقيعات للتحديث. عندما يتم ضبط هذه العلامة على false لن يتم تعديل المستند الأصلي مطلقًا.

**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


يحصل أو يضبط العلامة لإعادة حفظ المستند الأصلي عندما لا تحتوي طريقة Update على توقيعات للتحديث. إذا تم ضبط هذه العلامة على true (افتراضيًا) سيتم حفظ المستند مع سجل عملية التاريخ المقابل (التاريخ ونوع العملية) حتى إذا لم تحتوي طريقة Update على توقيعات للتحديث. عندما يتم ضبط هذه العلامة على false لن يتم تعديل المستند الأصلي مطلقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


يحصل أو يضبط العلامة لإعادة حفظ المستند الأصلي عندما لا تحتوي طريقة Delete على توقيعات متأثرة لإزالتها. إذا تم ضبط هذه العلامة على true (افتراضيًا) سيتم حفظ المستند مع سجل عملية التاريخ المقابل (التاريخ ونوع العملية) حتى إذا لم تحتوي طريقة Delete على توقيعات للإزالة. عندما يتم ضبط هذه العلامة على false لن يتم تعديل المستند الأصلي مطلقًا.

**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


يحصل أو يضبط العلامة لإعادة حفظ المستند الأصلي عندما لا تحتوي طريقة Delete على توقيعات متأثرة لإزالتها. إذا تم ضبط هذه العلامة على true (افتراضيًا) سيتم حفظ المستند مع سجل عملية التاريخ المقابل (التاريخ ونوع العملية) حتى إذا لم تحتوي طريقة Delete على توقيعات للإزالة. عندما يتم ضبط هذه العلامة على false لن يتم تعديل المستند الأصلي مطلقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


يحصل أو يضبط العلامة لتضمين توقيعات بيانات التعريف المدمجة القياسية مثل المؤلف، المالك، تاريخ إنشاء المستند، تاريخ التعديل، إلخ في قائمة البيانات الوصفية. إذا تم ضبط هذه العلامة على false (افتراضيًا) فإن GetDocumentInfo لن يتضمن هذه التوقيعات الوصفية. عندما يتم ضبط هذه العلامة على true ستتضمن معلومات المستند هذه التوقيعات الوصفية القياسية.

**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


يحصل أو يضبط العلامة لتضمين توقيعات بيانات التعريف المدمجة القياسية مثل المؤلف، المالك، تاريخ إنشاء المستند، تاريخ التعديل، إلخ في قائمة البيانات الوصفية. إذا تم ضبط هذه العلامة على false (افتراضيًا) فإن GetDocumentInfo لن يتضمن هذه التوقيعات الوصفية. عندما يتم ضبط هذه العلامة على true ستتضمن معلومات المستند هذه التوقيعات الوصفية القياسية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


تنفيذ المسجل المستخدم للتسجيل (الأخطاء، التحذيرات، المتتبعات). [ILogger](../../com.groupdocs.signature.logging/ilogger).

**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


مستوى التسجيل لتقييد الرسائل (All، Traces، Warnings، Errors). LogLevel. بشكل افتراضي يتم ضبط النوع All.

**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


مستوى التسجيل لتقييد الرسائل (All، Traces، Warnings، Errors). LogLevel. بشكل افتراضي يتم ضبط النوع All.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

