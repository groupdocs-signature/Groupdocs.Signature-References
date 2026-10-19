---
title: "PdfTextAnnotationAppearance"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يصف مظهر كائن تعليقات PDF النصية Title Subject Content."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

يصف مظهر كائن التعليق النصي في PDF (العنوان، الموضوع، المحتوى).

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | ينشئ كائن مظهر تعليقات نصية لتوقيع PDF. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | ينشئ تعليقات نصية لتوقيع PDF بالقيم المحددة (title, subject, contents). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getContents()](#getContents--) | يحصل أو يعيّن محتوى كائن التعليق. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | يحصل أو يعيّن محتوى كائن التعليق. |
|
|  | [getSubject()](#getSubject--) | يحصل أو يعيّن Subject الذي يمثل وصف الكائن. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | يحصل أو يعيّن Subject الذي يمثل وصف الكائن. |
|
|  | [getTitle()](#getTitle--) | الحصول أو تعيين عنوان سيُعرض في شريط عنوان كائن التعليق. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | الحصول أو تعيين عنوان سيُعرض في شريط عنوان كائن التعليق. |
|
|  | [getBorder()](#getBorder--) | الحصول أو تعيين إعدادات حدود مختلفة |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | الحصول أو تعيين إعدادات حدود مختلفة |
|
|  | [getBorderEffect()](#getBorderEffect--) | الحصول أو تعيين تأثير الحدود. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | الحصول أو تعيين تأثير الحدود. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | الحصول أو تعيين شدة تأثير الحدود. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | الحصول أو تعيين شدة تأثير الحدود. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | الحصول أو تعيين نصف قطر الزاوية الأفقية. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | الحصول أو تعيين نصف قطر الزاوية الأفقية. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | الحصول أو تعيين نصف قطر الزاوية العمودية. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | الحصول أو تعيين نصف قطر الزاوية العمودية. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


ينشئ كائن مظهر تعليقات نصية لتوقيع PDF.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


ينشئ تعليقات نصية لتوقيع PDF بالقيم المحددة (title, subject, contents).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | العنوان | java.lang.String | العنوان. |
|
|  | الموضوع | java.lang.String | الموضوع. |
|
|  | المحتويات | java.lang.String | المحتويات. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


يحصل أو يعيّن محتوى كائن التعليق.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


يحصل أو يعيّن محتوى كائن التعليق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


يحصل أو يعيّن Subject الذي يمثل وصف الكائن.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


يحصل أو يعيّن Subject الذي يمثل وصف الكائن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


الحصول أو تعيين عنوان سيُعرض في شريط عنوان كائن التعليق.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


الحصول أو تعيين عنوان سيُعرض في شريط عنوان كائن التعليق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


الحصول أو تعيين إعدادات حدود مختلفة


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


الحصول أو تعيين إعدادات حدود مختلفة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


الحصول أو تعيين تأثير الحدود.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


الحصول أو تعيين تأثير الحدود.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


الحصول أو تعيين شدة تأثير الحدود. النطاق الصالح للقيمة هو [0..2].


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


الحصول أو تعيين شدة تأثير الحدود. النطاق الصالح للقيمة هو [0..2].


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


الحصول أو تعيين نصف قطر الزاوية الأفقية.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


الحصول أو تعيين نصف قطر الزاوية الأفقية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


الحصول أو تعيين نصف قطر الزاوية العمودية.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


الحصول أو تعيين نصف قطر الزاوية العمودية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
