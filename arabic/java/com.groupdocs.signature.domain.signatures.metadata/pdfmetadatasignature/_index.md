---
title: "PdfMetadataSignature"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحتوي على خصائص توقيع بيانات تعريف PDF."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

يحتوي على خصائص توقيع بيانات تعريف PDF.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | ينشئ توقيع Pdf Metadata مع اسم محدد مسبقًا وقيمة فارغة |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | ينشئ توقيع Pdf Metadata مع قيم محددة مسبقًا |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | ينشئ توقيع Pdf Metadata مع قيم محددة مسبقًا |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | علامة البادئة لاسم توقيع Pdf Metadata. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | علامة البادئة لاسم توقيع Pdf Metadata. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص التوقيع |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
|  | [deepClone()](#deepClone--) | استنساخ كائن توقيع البيانات الوصفية. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | استنساخ كائن توقيع Pdf Metadata مع القيمة المعطاة. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


ينشئ توقيع Pdf Metadata مع اسم محدد مسبقًا وقيمة فارغة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم توقيع Pdf Metadata |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


ينشئ توقيع Pdf Metadata مع قيم محددة مسبقًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
|
|  | قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


ينشئ توقيع Pdf Metadata مع قيم محددة مسبقًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
|
|  | قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |
|
|  | العلامة | java.lang.String | علامة البادئة لتوقيع البيانات الوصفية |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


علامة البادئة لاسم توقيع Pdf Metadata. بشكل افتراضي يتم تعيين هذه الخاصية إلى "xmp".
القيم الممكنة هي


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


علامة البادئة لاسم توقيع Pdf Metadata. بشكل افتراضي يتم تعيين هذه الخاصية إلى "xmp".
القيم الممكنة هي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


يستبدل طريقة Equals لمقارنة خصائص التوقيع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التوقيع | java.lang.Object | كائن التوقيع للمقارنة معه. |
|

**Returns:**
boolean - يُعيد true إذا كان كائن التوقيع الممرّر له نفس النوع وجميع خصائصه مساوية لخصائص هذه الحالة.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يستبدل طريقة GetHashCode


**Returns:**
int - رمز التجزئة للتوقيع

### deepClone() {#deepClone--}
```
public Object deepClone()
```


استنساخ كائن توقيع البيانات الوصفية.


**Returns:**
java.lang.Object - يُرجِع نسخة مستنسخة من Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


استنساخ كائن توقيع Pdf Metadata مع القيمة المعطاة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | java.lang.Object | القيمة للكائن المستنسخ الجديد. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

