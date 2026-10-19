---
title: "MetadataSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل خيارات توقيع البيانات الوصفية."
type: docs
weight: 14
url: /ar/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

يمثل خيارات توقيع البيانات الوصفية.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | إنشاء نسخة جديدة من فئة SignMetadataOptions بالقيم الافتراضية. |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | إنشاء نسخة جديدة من فئة SignMetadataOptions مع البيانات الوصفية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | الحصول أو تعيين البيانات الوصفية للتوقيع. |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | الحصول أو تعيين البيانات الوصفية للتوقيع. |
|
|  | [getDataEncryption()](#getDataEncryption--) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات. |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | إنشاء PdfMetadataSignature جديد مع المعلمات الممررة وإضافته إلى المجموعة. |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | إنشاء ImageMetadataSignature جديد مع المعلمات الممررة وإضافته إلى المجموعة. |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | إضافة نسخة MetadataSignature الموجودة إلى المجموعة. |
|
|  | [validate()](#validate--) | طريقة داخلية للتحقق من صحة معلمات الخيارات. |
|
|  | [toString()](#toString--) | تجاوز تحويل السلسلة. |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


إنشاء نسخة جديدة من فئة SignMetadataOptions بالقيم الافتراضية.


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


إنشاء نسخة جديدة من فئة SignMetadataOptions مع البيانات الوصفية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | مجموعة توقيعات البيانات الوصفية [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


الحصول أو تعيين البيانات الوصفية للتوقيع.


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


الحصول أو تعيين البيانات الوصفية للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير نص توقيع QR-Code أو خصائص البيانات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


إنشاء PdfMetadataSignature جديد مع المعلمات الممررة وإضافته إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
|
|  | قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |
|
|  | العلامة | java.lang.String | علامة البادئة لتوقيع البيانات الوصفية |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


إنشاء ImageMetadataSignature جديد مع المعلمات الممررة وإضافته إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المعرّف | int | معرّف فريد لاسم توقيع البيانات الوصفية للصورة. راجع المراجع لمواصفات علامات Exif للقيم المحتملة للمعرّف |
|
|  | قيمة | java.lang.Object | قيمة البيانات الوصفية |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


إضافة نسخة MetadataSignature الموجودة إلى المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | مثيل MetadataSignature الحالي الذي سيتم إضافته |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


طريقة داخلية للتحقق من صحة معلمات الخيارات.


### toString() {#toString--}
```
public String toString()
```


تجاوز تحويل السلسلة.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
