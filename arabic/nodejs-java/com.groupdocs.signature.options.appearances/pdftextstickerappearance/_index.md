---
title: "PdfTextStickerAppearance"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يصف مظهر كائن ملصق التعليق النصي PDF ونافذة المنبثقة للملصق."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

يصف مظهر كائن ملصق التعليق النصي PDF ونافذة المنبثقة للملصق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | ينشئ كائن مظهر توضيح نص توقيع PDF. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTitle()](#getTitle--) | يحصل أو يضبط عنوان نافذة المنبثقة. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يحصل أو يضبط عنوان نافذة المنبثقة. |
| [getSubject()](#getSubject--) | يحصل أو يضبط الموضوع. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يحصل أو يضبط الموضوع. |
| [getContents()](#getContents--) | يحصل أو يضبط محتوى نافذة المنبثقة. |
| [setContents(String value)](#setContents-java.lang.String-) | يحصل أو يضبط محتوى نافذة المنبثقة. |
| [getOpened()](#getOpened--) | قم بإعداد ما إذا كانت نافذة ملصق المنبثقة سيفتح بشكل افتراضي. |
| [setOpened(boolean value)](#setOpened-boolean-) | قم بإعداد ما إذا كانت نافذة ملصق المنبثقة سيفتح بشكل افتراضي. |
| [getIcon()](#getIcon--) | يحصل أو يضبط أيقونة الملصق. |
| [setIcon(int value)](#setIcon-int-) | يحصل أو يضبط أيقونة الملصق. |
| [getDefaultAppearance()](#getDefaultAppearance--) | يحصل على المظهر الافتراضي للملصق. |
| [resetDefaultAppearance()](#resetDefaultAppearance--) | يمسح قيم المظهر الافتراضي للملصق. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


ينشئ كائن مظهر توضيح نص توقيع PDF.

### getTitle() {#getTitle--}
```
public final String getTitle()
```


يحصل أو يضبط عنوان نافذة المنبثقة.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


يحصل أو يضبط عنوان نافذة المنبثقة.

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


يحصل أو يضبط محتوى نافذة المنبثقة.

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


يحصل أو يضبط محتوى نافذة المنبثقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


قم بإعداد ما إذا كانت نافذة ملصق المنبثقة سيفتح بشكل افتراضي.

**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


قم بإعداد ما إذا كانت نافذة ملصق المنبثقة سيفتح بشكل افتراضي.

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


يحصل على المظهر الافتراضي للملصق. تُطبق هذه الخصائص كقيمة افتراضية إذا لم يتم تحديد خاصية Options.SignatureAppearance. يمكن للمستخدم تغيير هذه الخصائص في أي وقت.

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
