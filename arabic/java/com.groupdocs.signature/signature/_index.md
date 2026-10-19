---
title: "توقيع"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق وخيارات التحميل |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق و[SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق، خيارات التحميل |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) وإعدادات [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف و |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف و[SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف، |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) و [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | يتحقق من توقيعات المستند باستخدام قائمة من بيانات VerifyOptions. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة والمرشحات |
النتائج الناجحة حسب الشرط المحدد.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | يتحقق من توقيعات المستند باستخدام قائمة من خيارات التحقق ويصفّي |
النتائج الناجحة حسب الشرط المحدد.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | يحصل على معلومات حول صفحات المستند: أحجامها، |
الارتفاع الأقصى للصفحة، عرض الصفحة ذات الارتفاع الأقصى.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | ينشئ معاينة لصفحات المستند. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | يبحث عن التوقيعات في مستند باستخدام قائمة من [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | يبحث عن التوقيعات باستخدام قائمة من الخيارات ويصفّي النتيجة حسب شرط. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | يبحث عن التوقيعات في مستند باستخدام خيارات [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | يبحث عن توقيعات من النوع المحدد في المستند، مع إمكانية تصفيتها حسب شرط. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | يبحث عن النوع الدقيق للتوقيعات في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [search(int[] signatureTypes)](#search-int...-) | يبحث عن أنواع التوقيع المحددة في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | يقوم بتحديث توقيع [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) الممرَّ في المستند. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | تحديث التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | تحديث التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | تحديث التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | حذف التوقيع الممرر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | حذف قائمة التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | حذف التوقيع الممرر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | حذف قائمة التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | حذف التواقيع من النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | حذف التواقيع من قائمة الأنواع المحددة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | حذف التواقيع من النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | حذف التواقيع من قائمة الأنواع المحددة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | حذف التوقيع بواسطة معرف التوقيع المحدد من المستند. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | حذف قائمة التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | إنشاء معاينة التوقيع بناءً على SignOptions المعطاة. |
|
|  | [dispose()](#dispose--) | تنفيذ واجهة IDisposable لتنظيف الموارد الداخلية. |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.InputStream | دفق محتوى المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق وخيارات التحميل
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.InputStream | دفق محتوى المستند. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق و[SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.InputStream | دفق محتوى المستند. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر الدفق، خيارات التحميل
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) وإعدادات [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.InputStream | دفق محتوى المستند. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مطلق أو نسبي. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف و
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مطلق أو نسبي. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)
* More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/loading/)

<br />

|

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف و[SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مطلق أو نسبي. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

<br />

*** ** * ** ***

 **Learn more** 

* 
* 

<br />

|

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


ينشئ نسخة جديدة من الفئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند يُقدَّم عبر مسار الملف،
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) و [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مطلق أو نسبي. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/supported-document-formats/)
* More about GroupDocs.Signature for Java features: [Developer Guide](../https://docs.groupdocs.com/signature/java/developer-guide/)

<br />

|

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)
```


يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList)
```


يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions)
```


يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, SignOptions signOptions, SaveOptions saveOptions) {#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)
```


يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### sign(String filePath, List<SignOptions> signOptionsList) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList)
```


يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - 
### sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions) {#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-}
```
public final SignResult sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)
```


يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

<br />

*** ** * ** ***

**Learn more**

* More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/electronic-signature-types/)
* More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/signing/)
* More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/saving/)

<br />

|

**Returns:**
[SignResult](../../com.groupdocs.signature.domain/signresult) - Returns instance of [SignResult](../../com.groupdocs.signature.domain/signresult) with list of newly created signatures.

### verify(VerifyOptions verifyOptions) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-}
```
public final VerificationResult verify(VerifyOptions verifyOptions)
```


يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | خيارات التحقق من التوقيع. |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(List<VerifyOptions> verifyOptionsList) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--}
```
public final VerificationResult verify(List<VerifyOptions> verifyOptionsList)
```


يتحقق من توقيعات المستند باستخدام قائمة من بيانات VerifyOptions.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | مجموعة خيارات التحقق من التوقيع. مثال على [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

<br />

*** ** * ** ***

**Learn more**

* More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java](../https://docs.groupdocs.com/signature/java/verify-document-for-signatures/)

<br />

|

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.

### verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate) {#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)
```


يتحقق من توقيعات المستند باستخدام خيارات التحقق المقدمة والمرشحات
النتائج الناجحة حسب الشرط المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | خيارات التحقق من التوقيع. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | دالة الترشيح المطبقة على قائمة التوقيعات التي تم التحقق منها. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - قائمة بالتوقيعات التي نجحت في التحقق وتلبت شرط الدالة.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


يتحقق من توقيعات المستند باستخدام قائمة من خيارات التحقق ويصفّي
النتائج الناجحة حسب الشرط المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | قائمة خيارات التحقق من التوقيع. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | دالة الترشيح المطبقة على قائمة التوقيعات التي تم التحقق منها. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - قائمة بالتوقيعات التي نجحت في التحقق وتلبت شرط الدالة.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على معلومات حول صفحات المستند: أحجامها،
الارتفاع الأقصى للصفحة، عرض الصفحة ذات الارتفاع الأقصى.


**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

<br />

*** ** * ** ***

**Learn more**

* Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java](../https://docs.groupdocs.com/signature/java/get-document-information/)

<br />


### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


ينشئ معاينة لصفحات المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | خيارات المعاينة. |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/generate-document-pages-preview/)

<br />

|

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


يبحث عن التوقيعات في مستند باستخدام قائمة من [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | مجموعة خيارات البحث. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.

### search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)
```


يبحث عن التوقيعات باستخدام قائمة من الخيارات ويصفّي النتيجة حسب شرط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | قائمة خيارات البحث. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | دالة الترشيح المستخدمة لتصفية التوقيعات الناتجة. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


يبحث عن التوقيعات في مستند باستخدام خيارات [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | خيارات البحث. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - يُرجع قائمة التوقيعات التي تم العثور عليها.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


يبحث عن توقيعات من النوع المحدد في المستند، مع إمكانية تصفيتها حسب شرط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | معامل النوع العام لـ [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | خيارات البحث عن التوقيع. |
|
|  | predicate | java.util.function.Predicate<T> | مرشح دالة اختياري يُطبق بعد البحث. قد يكون null. |
|

**Returns:**
java.util.List<T> - قائمة بالتوقيعات التي تم العثور عليها، يمكن تصفيتها اختياريًا بواسطة الدالة.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


يبحث عن النوع الدقيق للتوقيعات في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | نوع التوقيعات للبحث. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - يُرجع قائمة التوقيعات التي تم العثور عليها بالنوع الدقيق.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


يبحث عن أنواع التوقيع المحددة في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureTypes | int[] | نوع أو عدة أنواع من التوقيعات للعثور عليها. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.

### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


يقوم بتحديث توقيع [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) الممرَّ في المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع الذي سيتم تحديثه في المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - يُعيد true إذا كانت العملية ناجحة.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


تحديث التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لتحديثها في المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


تحديث التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لتحديثها في المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


تحديث التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع الذي سيتم تحديثه في المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - يُعيد UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) مع قائمة بالتوقيعات التي تم تحديثها بنجاح وتلك التي فشلت.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


حذف التوقيع الممرر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع لإزالته من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - يُعيد true إذا كانت العملية ناجحة.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


حذف قائمة التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لإزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


حذف التوقيع الممرر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع لإزالته من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - يُعيد true إذا كانت العملية ناجحة.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


حذف قائمة التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لإزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


حذف التواقيع من النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند.
فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة كـ Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) سيتم إزالتها.
الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signatureType | int | نوع التوقيعات التي سيتم إزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


حذف التواقيع من قائمة الأنواع المحددة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند.
فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة كـ Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) سيتم إزالتها.
الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المستند | java.io.OutputStream | دفق المستند الناتج. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | قائمة أنواع التوقيعات التي سيتم إزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


حذف التواقيع من النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند.
فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة كـ Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) سيتم إزالتها.
الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signatureType | int | نوع التوقيعات التي سيتم إزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


حذف التواقيع من قائمة الأنواع المحددة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند.
فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة كـ Signatures
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) سيتم إزالتها.
الأنواع التالية من التوقيعات مدعومة: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف الناتج. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | قائمة أنواع التوقيعات التي سيتم إزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


حذف التوقيع بواسطة معرف التوقيع المحدد من المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureId | java.lang.String | معرّف Id للتوقيع الذي سيتم إزالته من المستند. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - يُعيد true إذا كانت العملية ناجحة.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


حذف قائمة التواقيع الممررة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | قائمة معرفات التوقيعات التي سيتم إزالتها من المستند. |

<br />

*** ** * ** ***

**Learn more** /// /// /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents) /// /// /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting) /// /// ///
|

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.

### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


ينشئ معاينة التوقيع بناءً على SignOptions المعطاة. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | معاينة التوقيع مع SignOptions المعطاة. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


تنفيذ واجهة IDisposable لتنظيف الموارد الداخلية.


