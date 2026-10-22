---
title: "MetadataSignOptions"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل خيارات توقيع البيانات الوصفية."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

يمثل خيارات توقيع البيانات الوصفية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MetadataSignOptions()](#MetadataSignOptions--) | ينشئ مثيلاً جديدًا من فئة SignMetadataOptions بالقيم الافتراضية. |
| [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | ينشئ مثيلاً جديدًا من فئة SignMetadataOptions مع البيانات الوصفية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSignatures()](#getSignatures--) | الحصول أو تعيين البيانات الوصفية للتوقيع. |
| [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | الحصول أو تعيين البيانات الوصفية للتوقيع. |
| [getDataEncryption()](#getDataEncryption--) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code. |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code. |
| [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | ينشئ PdfMetadataSignature جديدًا بالمعاملات الممررة ويضيفه إلى المجموعة. |
| [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | ينشئ ImageMetadataSignature جديدًا بالمعاملات الممررة ويضيفه إلى المجموعة. |
| [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | إضافة نسخة MetadataSignature الموجودة إلى المجموعة. |
| [validate()](#validate--) | طريقة داخلية للتحقق من صحة معلمات الخيارات. |
| [toString()](#toString--) | تجاوز تحويل السلسلة. |
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


ينشئ مثيلاً جديدًا من فئة SignMetadataOptions بالقيم الافتراضية.

### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


ينشئ مثيلاً جديدًا من فئة SignMetadataOptions مع البيانات الوصفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | مجموعة من توقيعات البيانات الوصفية [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature). |

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


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code.

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


الحصول أو تعيين تنفيذ واجهة [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) لتشفير وفك تشفير خصائص نص أو بيانات توقيع QR-Code.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


ينشئ PdfMetadataSignature جديدًا بالمعاملات الممررة ويضيفه إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | اسم كائن توقيع البيانات الوصفية |
| قيمة | java.lang.Object | قيمة توقيع البيانات الوصفية |
| العلامة | java.lang.String | علامة البادئة لتوقيع البيانات الوصفية |

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection
### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


ينشئ ImageMetadataSignature جديدًا بالمعاملات الممررة ويضيفه إلى المجموعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المعرّف | int | معرّف فريد لاسم توقيع بيانات الصورة الوصفية. راجع المراجع لمواصفات علامات Exif للحصول على القيم المحتملة للمعرّف. |
| قيمة | java.lang.Object | قيمة البيانات الوصفية |

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
| metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | مثيل MetadataSignature الحالي الذي سيتم إضافته |

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
