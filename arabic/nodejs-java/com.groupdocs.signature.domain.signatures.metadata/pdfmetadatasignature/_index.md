---
title: "PdfMetadataSignature"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحتوي على خصائص توقيع بيانات PDF الوصفية."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات PDF الوصفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | ينشئ توقيع بيانات تعريف Pdf باسم محدد مسبقًا وقيمة فارغة |
| [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | ينشئ توقيع بيانات تعريف Pdf بقيم محددة مسبقًا |
| [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | ينشئ توقيع بيانات تعريف Pdf بقيم محددة مسبقًا |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTagPrefix()](#getTagPrefix--) | علامة البادئة لاسم توقيع بيانات تعريف Pdf. |
| [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | علامة البادئة لاسم توقيع بيانات تعريف Pdf. |
| [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع. |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
| [deepClone()](#deepClone--) | استنساخ كائن توقيع Metadata. |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ كائن توقيع بيانات تعريف Pdf بالقيمة المعطاة. |
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


ينشئ توقيع بيانات تعريف Pdf باسم محدد مسبقًا وقيمة فارغة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم توقيع بيانات تعريف Pdf |

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


ينشئ توقيع بيانات تعريف Pdf بقيم محددة مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
| قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


ينشئ توقيع بيانات تعريف Pdf بقيم محددة مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
| قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |
| العلامة | java.lang.String | علامة البادئة لتوقيع البيانات الوصفية |

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


علامة البادئة لاسم توقيع بيانات تعريف Pdf. بشكل افتراضي يتم تعيين هذه الخاصية إلى "xmp". القيم الممكنة هي

**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


علامة البادئة لاسم توقيع بيانات تعريف Pdf. بشكل افتراضي يتم تعيين هذه الخاصية إلى "xmp". القيم الممكنة هي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| توقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |

**Returns:**
boolean - يُرجِع true إذا كان كائن التوقيع الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذا الكائن.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int - رمز التجزئة للتوقيع
### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ كائن توقيع Metadata.

**Returns:**
java.lang.Object - يعيد نسخة مستنسخة من كائن توقيع Metadata
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


استنساخ كائن توقيع بيانات تعريف Pdf بالقيمة المعطاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.Object | قيمة للكائن المستنسخ الجديد. |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
