---
title: "PdfTextStickerAppearance"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يصف مظهر كائن ملصق التعليق النصي في PDF ونافذة المنبثقة للملصق."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

يصف مظهر كائن ملصق التعليق النصي في PDF ونافذة المنبثقة للملصق.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | ينشئ كائن مظهر التعليق النصي لتوقيع PDF. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTitle()](#getTitle--) | يحصل أو يضبط عنوان نافذة منبثقة. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | يحصل أو يضبط عنوان نافذة منبثقة. |
|
|  | [getSubject()](#getSubject--) | يحصل أو يضبط الموضوع. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | يحصل أو يضبط الموضوع. |
|
|  | [getContents()](#getContents--) | يحصل أو يضبط محتوى نافذة منبثقة. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | يحصل أو يضبط محتوى نافذة منبثقة. |
|
|  | [getOpened()](#getOpened--) | حدد ما إذا كانت نافذة ملصق منبثقة ستفتح افتراضيًا. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | حدد ما إذا كانت نافذة ملصق منبثقة ستفتح افتراضيًا. |
|
|  | [getIcon()](#getIcon--) | يحصل أو يضبط أيقونة الملصق. |
|
|  | [setIcon(int value)](#setIcon-int-) | يحصل أو يضبط أيقونة الملصق. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | يحصل على المظهر الافتراضي للملصق. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | يمسح قيم المظهر الافتراضي للملصق. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


ينشئ كائن مظهر التعليق النصي لتوقيع PDF.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


يحصل أو يضبط عنوان نافذة منبثقة.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


يحصل أو يضبط عنوان نافذة منبثقة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


يحصل أو يضبط الموضوع.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


يحصل أو يضبط الموضوع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


يحصل أو يضبط محتوى نافذة منبثقة.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


يحصل أو يضبط محتوى نافذة منبثقة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


حدد ما إذا كانت نافذة ملصق منبثقة ستفتح افتراضيًا.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


حدد ما إذا كانت نافذة ملصق منبثقة ستفتح افتراضيًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


يحصل أو يضبط أيقونة الملصق.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


يحصل أو يضبط أيقونة الملصق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


يحصل على المظهر الافتراضي للملصق. تُطبق هذه الخصائص كقيمة افتراضية إذا
خاصية Options.SignatureAppearance غير محددة.
يمكن للمستخدم تغيير الخصائص في أي وقت.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


يمسح قيم المظهر الافتراضي للملصق.


### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
