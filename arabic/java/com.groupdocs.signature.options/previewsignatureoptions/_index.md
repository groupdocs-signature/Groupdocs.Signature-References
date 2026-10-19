---
title: "PreviewSignatureOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات معاينة التوقيع."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

يمثل خيارات معاينة التوقيع.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | يُهيئ كائن PreviewSignatureOptions. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | قيمة فريدة لتمييز التوقيع. |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | قيمة فريدة لتمييز التوقيع. |
|
|  | [getSignOptions()](#getSignOptions--) | خيارات التوقيع لتوليد معاينة. |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | خيارات التوقيع لتوليد معاينة. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | يحصل أو يضبط تنسيق صور المعاينة. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | يحصل أو يضبط تنسيق صور المعاينة. |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


يُهيئ كائن PreviewSignatureOptions.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع لتوليد المعاينة. |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | واجهة تُعرّف الطريقة لإنشاء تدفق معاينة صفحة الإخراج. |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


قيمة فريدة لتمييز التوقيع.
استخدم SignatureId لتحديد خيارات المعاينة.


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


قيمة فريدة لتمييز التوقيع.
استخدم SignatureId لتحديد خيارات المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


خيارات التوقيع لتوليد معاينة.


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


خيارات التوقيع لتوليد معاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


يحصل أو يضبط تنسيق صور المعاينة.
القيمة الافتراضية هي PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


يحصل أو يضبط تنسيق صور المعاينة.
القيمة الافتراضية هي PNG


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

