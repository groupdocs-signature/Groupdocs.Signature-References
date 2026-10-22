---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات معاينة التوقيع."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

يمثل خيارات معاينة التوقيع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | يقوم بتهيئة كائن PreviewSignatureOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSignatureId()](#getSignatureId--) | قيمة فريدة لتمييز التوقيع. |
| [setSignatureId(String value)](#setSignatureId-java.lang.String-) | قيمة فريدة لتمييز التوقيع. |
| [getSignOptions()](#getSignOptions--) | خيارات التوقيع لتوليد المعاينة. |
| [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | خيارات التوقيع لتوليد المعاينة. |
| [getPreviewFormat()](#getPreviewFormat--) | يحصل أو يضبط تنسيق صور المعاينة. |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | يحصل أو يضبط تنسيق صور المعاينة. |
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


يقوم بتهيئة كائن PreviewSignatureOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع لتوليد المعاينة لها. |
| pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | الواجهة التي تعرف الطريقة لإنشاء تدفق معاينة صفحة الإخراج. |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


قيمة فريدة لتمييز التوقيع. استخدم SignatureId لتحديد خيارات المعاينة.

**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


قيمة فريدة لتمييز التوقيع. استخدم SignatureId لتحديد خيارات المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


خيارات التوقيع لتوليد المعاينة.

**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


خيارات التوقيع لتوليد المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


يحصل أو يضبط تنسيق صور المعاينة. القيمة الافتراضية هي PNG

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


يحصل أو يضبط تنسيق صور المعاينة. القيمة الافتراضية هي PNG

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

