---
title: "PreviewOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات معاينة المستند."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

يمثل خيارات معاينة المستند.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | يُهيئ كائن PreviewOptions. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | يُهيئ كائن PreviewOptions. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | يُهيئ كائن PreviewOptions. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يحصل أو يعيّن عرض صور المعاينة. |
|
|  | [setWidth(int value)](#setWidth-int-) | يحصل أو يعيّن عرض صور المعاينة. |
|
|  | [getHeight()](#getHeight--) | يحصل أو يعيّن ارتفاع صور المعاينة. |
|
|  | [setHeight(int value)](#setHeight-int-) | يحصل أو يعيّن ارتفاع صور المعاينة. |
|
|  | [getPageNumbers()](#getPageNumbers--) | يحصل أو يعيّن أرقام صفحات صور المعاينة. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | يحصل أو يعيّن أرقام صفحات صور المعاينة. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | يحصل أو يضبط تنسيق صور المعاينة. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | يحصل أو يضبط تنسيق صور المعاينة. |
|
|  | [getHideSignatures()](#getHideSignatures--) | يحصل أو يعيّن العلامة لإخفاء التوقيعات من صورة معاينة الصفحة. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | يحصل أو يعيّن العلامة لإخفاء التوقيعات من صورة معاينة الصفحة. |
|
|  | [getResolution()](#getResolution--) | يحصل على دقة صور المعاينة بوحدة DPI (نقطة في البوصة). |
|
|  | [setResolution(int value)](#setResolution-int-) | يعيّن دقة صور المعاينة بوحدة DPI (نقطة في البوصة). |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


يُهيئ كائن PreviewOptions.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | واجهة تُعرّف الطريقة لإنشاء تدفق معاينة صفحة الإخراج. |
|
|  | pageNumbers | int[] | أرقام الصفحات المطلوبة |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


يُهيئ كائن PreviewOptions.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | واجهة تُعرّف الطريقة لإنشاء تدفق معاينة صفحة الإخراج. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


يُهيئ كائن PreviewOptions.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | مسار ملف الإخراج. |
|
|  | pageNumbers | int[] | أرقام الصفحات المطلوبة |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل أو يعيّن عرض صور المعاينة.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يحصل أو يعيّن عرض صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل أو يعيّن ارتفاع صور المعاينة.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يحصل أو يعيّن ارتفاع صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


يحصل أو يعيّن أرقام صفحات صور المعاينة.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


يحصل أو يعيّن أرقام صفحات صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


يحصل أو يضبط تنسيق صور المعاينة.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


يحصل أو يضبط تنسيق صور المعاينة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


يحصل أو يعيّن العلامة لإخفاء التوقيعات من صورة معاينة الصفحة.
سيتم إخفاء التوقيعات التي تم وضع علامة IsSignature عليها فقط من صورة صفحة المستند المُولدة.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


يحصل أو يعيّن العلامة لإخفاء التوقيعات من صورة معاينة الصفحة.
سيتم إخفاء التوقيعات التي تم وضع علامة IsSignature عليها فقط من صورة صفحة المستند المُولدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


يحصل على دقة صور المعاينة بوحدة DPI (نقطة في البوصة).


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


يعيّن دقة صور المعاينة بوحدة DPI (نقطة في البوصة).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

