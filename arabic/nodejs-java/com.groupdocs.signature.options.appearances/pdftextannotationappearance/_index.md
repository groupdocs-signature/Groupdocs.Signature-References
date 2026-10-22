---
title: "PdfTextAnnotationAppearance"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يصف مظهر كائن تعليقات النص PDF العنوان والموضوع والمحتوى."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

يصف مظهر كائن التعليق النصي PDF (العنوان، الموضوع، المحتوى).
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | ينشئ كائن مظهر تعليقات نص التوقيع PDF. |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | ينشئ تعليقات نص التوقيع PDF بالقيم المحددة (العنوان، الموضوع، المحتويات). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getContents()](#getContents--) | يحصل أو يعيّن محتوى كائن التعليق. |
| [setContents(String value)](#setContents-java.lang.String-) | يحصل أو يعيّن محتوى كائن التعليق. |
| [getSubject()](#getSubject--) | يحصل أو يعيّن الموضوع الذي يمثل وصف الكائن. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يحصل أو يعيّن الموضوع الذي يمثل وصف الكائن. |
| [getTitle()](#getTitle--) | يحصل أو يضبط عنوانًا سيتم عرضه في شريط عنوان كائن التعليق. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يحصل أو يضبط عنوانًا سيتم عرضه في شريط عنوان كائن التعليق. |
| [getBorder()](#getBorder--) | يحصل أو يضبط إعدادات الحدود المختلفة |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | يحصل أو يضبط إعدادات الحدود المختلفة |
| [getBorderEffect()](#getBorderEffect--) | يحصل أو يضبط تأثير الحدود. |
| [setBorderEffect(int value)](#setBorderEffect-int-) | يحصل أو يضبط تأثير الحدود. |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | يحصل أو يضبط شدة تأثير الحدود. |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | يحصل أو يضبط شدة تأثير الحدود. |
| [getHCornerRadius()](#getHCornerRadius--) | يحصل أو يضبط نصف قطر الزاوية الأفقية. |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | يحصل أو يضبط نصف قطر الزاوية الأفقية. |
| [getVCornerRadius()](#getVCornerRadius--) | يحصل أو يضبط نصف قطر الزاوية العمودية. |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | يحصل أو يضبط نصف قطر الزاوية العمودية. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


ينشئ كائن مظهر تعليقات نص التوقيع PDF.

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


ينشئ تعليقات نص التوقيع PDF بالقيم المحددة (العنوان، الموضوع، المحتويات).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | java.lang.String | العنوان. |
| الموضوع | java.lang.String | الموضوع. |
| المحتويات | java.lang.String | المحتويات. |

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


يحصل أو يعيّن الموضوع الذي يمثل وصف الكائن.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


يحصل أو يعيّن الموضوع الذي يمثل وصف الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


يحصل أو يضبط عنوانًا سيتم عرضه في شريط عنوان كائن التعليق.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


يحصل أو يضبط عنوانًا سيتم عرضه في شريط عنوان كائن التعليق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


يحصل أو يضبط إعدادات الحدود المختلفة

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


يحصل أو يضبط إعدادات الحدود المختلفة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


يحصل أو يضبط تأثير الحدود.

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


يحصل أو يضبط تأثير الحدود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


يحصل أو يضبط شدة تأثير الحدود. النطاق الصالح للقيمة هو [0..2].

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


يحصل أو يضبط شدة تأثير الحدود. النطاق الصالح للقيمة هو [0..2].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


يحصل أو يضبط نصف قطر الزاوية الأفقية.

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


يحصل أو يضبط نصف قطر الزاوية الأفقية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


يحصل أو يضبط نصف قطر الزاوية العمودية.

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


يحصل أو يضبط نصف قطر الزاوية العمودية.

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
