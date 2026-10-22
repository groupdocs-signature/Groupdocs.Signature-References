---
title: "التوقيع"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

يمثل الفئة الرئيسية التي تتحكم في عملية توقيع المستند.

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق. |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق وخيارات التحميل LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق و[SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق، خيارات التحميل LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) والإعدادات [SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath)](#Signature-java.lang.String-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف. |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف وLoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)). |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف و[SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف، LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) و[SignatureSettings](../../com.groupdocs.signature/signaturesettings). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق. |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق. |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد. |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد. |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | يوقع المستند بمجموعة من [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى مسار ملف محدد مع [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) المحددة مسبقًا. |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | يتحقق من توقيعات المستند باستخدام بيانات VerifyOptions المعطاة. |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | يتحقق من توقيعات المستند باستخدام قائمة من بيانات VerifyOptions. |
| [getDocumentInfo()](#getDocumentInfo--) | يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، وعرض الصفحة ذات أقصى ارتفاع. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | ينشئ معاينة لصفحات المستند. |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | يبحث عن التوقيعات في المستند باستخدام قائمة من [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | يبحث عن التوقيعات في المستند باستخدام خيارات [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions). |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | يبحث عن النوع الدقيق للتوقيعات في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [search(int[] signatureTypes)](#search-int...-) | يبحث عن أنواع التوقيعات المحددة في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype). |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | يقوم بتحديث التوقيع الممرّر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | يقوم بتحديث التوقيعات الممرّرة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | يقوم بتحديث التوقيعات الممرّرة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | يقوم بتحديث التوقيعات الممرّرة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند. |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | يحذف التوقيع الممرّر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | يحذف القائمة الممرّرة من التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | يحذف التوقيع الممرّر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | يحذف القائمة الممرّرة من التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | يحذف توقيعات النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | يحذف توقيعات القائمة المحددة من الأنواع [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | يحذف توقيعات النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | يحذف توقيعات القائمة المحددة من الأنواع [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. |
| [delete(String signatureId)](#delete-java.lang.String-) | يحذف التوقيع وفقًا لمعرّف التوقيع المحدد من المستند. |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | يحذف القائمة الممرّرة من التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند. |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | ينشئ معاينة للتوقيع بناءً على SignOptions المعطاة. |
| [dispose()](#dispose--) | تنفيذ واجهة IDisposable لتنظيف الموارد الداخلية |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | دفق محتوى المستند. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(InputStream document, LoadOptions loadOptions)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق وخيارات التحميل LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | دفق محتوى المستند. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(InputStream document, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, SignatureSettings settings)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق و[SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | دفق محتوى المستند. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر تدفق، خيارات التحميل LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) والإعدادات [SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.InputStream | دفق محتوى المستند. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath) {#Signature-java.lang.String-}
```
public Signature(String filePath)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار ملف مطلق أو نسبي. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### Signature(String filePath, LoadOptions loadOptions) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-}
```
public Signature(String filePath, LoadOptions loadOptions)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف وLoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف مطلق أو نسبي. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]
 *  More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/
[Load and eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/loading/ |

### Signature(String filePath, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, SignatureSettings settings)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف و[SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف مطلق أو نسبي. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


ينشئ نسخة جديدة من فئة [Signature](../../com.groupdocs.signature/signature) باستخدام مستند مقدم عبر مسار الملف، LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) و[SignatureSettings](../../com.groupdocs.signature/signaturesettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف مطلق أو نسبي. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | خيارات تحميل المستند. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | إعدادات التوقيع. |

--------------------

**Learn more**

 *  More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature][]
 *  More about GroupDocs.Signature for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/supported-document-formats/
[Developer Guide]: https://docs.groupdocs.com/signature/java/developer-guide/ |

### sign(OutputStream document, SignOptions signOptions) {#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-}
```
public final SignResult sign(OutputStream document, SignOptions signOptions)
```


يوقع المستند باستخدام [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ويحفظ النتيجة إلى تدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| مستند | java.io.OutputStream | دفق المستند الناتج. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| مستند | java.io.OutputStream | دفق المستند الناتج. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| filePath | java.lang.String | مسار ملف الإخراج. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | خيارات التوقيع. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/ |

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
| filePath | java.lang.String | مسار ملف الإخراج. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | قائمة خيارات التوقيع. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | خيارات الحفظ. |

--------------------

**Learn more**

 *  More about electronic signature types supported by GroupDocs.Signature: [Electronic signature types supported by GroupDocs.Signature][]
 *  More about how eSign documents in Java: [How to eSign documents using GroupDocs.Signature][]
 *  More about how save electronically signed documents and customize saving process: [How to customize electronically signed documents on save using GroupDocs.Signature][]


[Electronic signature types supported by GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/electronic-signature-types/
[How to eSign documents using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/signing/
[How to customize electronically signed documents on save using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/saving/ |

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

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

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
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | مجموعة خيارات التحقق من التوقيع. مثيل لـ [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

--------------------

**Learn more**

 *  More about electronically signed documents verification using GroupDocs.Signature: [How to verify document is electronically signed in Java][]


[How to verify document is electronically signed in Java]: https://docs.groupdocs.com/signature/java/verify-document-for-signatures/ |

**Returns:**
[VerificationResult](../../com.groupdocs.signature.domain/verificationresult) - Returns instance of [VerificationResult](../../com.groupdocs.signature.domain/verificationresult). Property VerificationResult.IsValid returns true if verification process was successful.
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على معلومات حول صفحات المستند: أحجامها، أقصى ارتفاع للصفحة، وعرض الصفحة ذات أقصى ارتفاع.

**Returns:**
[IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo) - Information about document.

--------------------

**Learn more**

 *  Learn more about signed document - file type, pages count and many other format specific properties: [How to get document properties in Java][]


[How to get document properties in Java]: https://docs.groupdocs.com/signature/java/get-document-information/
### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


ينشئ معاينة لصفحات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | خيارات المعاينة. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


يبحث عن التوقيعات في المستند باستخدام قائمة من [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | مجموعة خيارات البحث. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found Signatures.
### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


يبحث عن التوقيعات في المستند باستخدام خيارات [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | خيارات البحث. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - يُرجِع قائمة التوقيعات التي تم العثور عليها.
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

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - يُرجِع قائمة التوقيعات التي تم العثور عليها بالنوع الدقيق.
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


يبحث عن أنواع التوقيعات المحددة في المستند باستخدام قيمة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureTypes | int[] | نوع أو عدة أنواع من التوقيعات للعثور عليها. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - Returns instance of [SearchResult](../../com.groupdocs.signature.domain/searchresult) with list of found signatures.
### update(OutputStream document, BaseSignature signature) {#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(OutputStream document, BaseSignature signature)
```


يقوم بتحديث التوقيع الممرّر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع لتحديثه في المستند. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
منطقي - يُرجع true إذا نجحت العملية.
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


يقوم بتحديث التوقيعات الممرّرة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لتحديثها في المستند. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, List<BaseSignature> signatures) {#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(String filePath, List<BaseSignature> signatures)
```


يقوم بتحديث التوقيعات الممرّرة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لتحديثها في المستند. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
[UpdateResult](../../com.groupdocs.signature.domain/updateresult) - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.
### update(String filePath, BaseSignature signature) {#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean update(String filePath, BaseSignature signature)
```


يقوم بتحديث التوقيعات الممرّرة [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) في المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع لتحديثه في المستند. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
منطقية - تُرجع UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) مع قائمة التوقيعات التي تم تحديثها بنجاح وتلك التي فشلت.
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


يحذف التوقيع الممرّر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع الذي سيتم إزالته من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
منطقي - يُرجع true إذا نجحت العملية.
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


يحذف القائمة الممرّرة من التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لإزالتها من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, BaseSignature signature) {#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(String filePath, BaseSignature signature)
```


يحذف التوقيع الممرّر [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | كائن التوقيع الذي سيتم إزالته من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
منطقي - يُرجع true إذا نجحت العملية.
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


يحذف القائمة الممرّرة من التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | التوقيعات | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | قائمة التوقيعات لإزالتها من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(OutputStream document, int signatureType) {#delete-java.io.OutputStream-int-}
```
public final DeleteResult delete(OutputStream document, int signatureType)
```


يحذف التوقيعات من النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. سيتم حذف فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة عليها كـ Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) . الأنواع التالية من التوقيعات مدعومة: نص، صورة، رقمية، باركود، رمز QR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | signatureType | int | نوع التوقيعات التي سيتم إزالتها من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete+signatures+of+the+certain+type/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(OutputStream document, List<Integer> signatureTypes) {#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(OutputStream document, List<Integer> signatureTypes)
```


يحذف التوقيعات من قائمة الأنواع المحددة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. سيتم حذف فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة عليها كـ Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) . الأنواع التالية من التوقيعات مدعومة: نص، صورة، رقمية، باركود، رمز QR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | java.io.OutputStream | دفق المستند الناتج. |
|  | signatureTypes | java.util.List<java.lang.Integer> | قائمة أنواع التوقيعات التي سيتم إزالتها من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String filePath, int signatureType) {#delete-java.lang.String-int-}
```
public final DeleteResult delete(String filePath, int signatureType)
```


يحذف التوقيعات من النوع المحدد [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. سيتم حذف فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة عليها كـ Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) . الأنواع التالية من التوقيعات مدعومة: نص، صورة، رقمية، باركود، رمز QR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | signatureType | int | نوع التوقيعات التي سيتم إزالتها من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignatures with specific type from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignatures with specific type from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### deleteByTypes(String filePath, List<Integer> signatureTypes) {#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--}
```
public final DeleteResult deleteByTypes(String filePath, List<Integer> signatureTypes)
```


يحذف التوقيعات من قائمة الأنواع المحددة [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) من المستند. سيتم حذف فقط التوقيعات التي تم إضافتها بواسطة طريقة Sign وتم وضع علامة عليها كـ Signatures  BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) . الأنواع التالية من التوقيعات مدعومة: نص، صورة، رقمية، باركود، رمز QR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الإخراج. |
|  | signatureTypes | java.util.List<java.lang.Integer> | قائمة أنواع التوقيعات التي سيتم إزالتها من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### delete(String signatureId) {#delete-java.lang.String-}
```
public final boolean delete(String signatureId)
```


يحذف التوقيع وفقًا لمعرّف التوقيع المحدد من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureId | java.lang.String | معرّف التوقيع الذي سيتم إزالته من المستند. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
منطقي - يُرجع true إذا نجحت العملية.
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


يحذف القائمة الممرّرة من التوقيعات [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | قائمة معرفات التوقيعات التي سيتم إزالتها من المستند. |

--------------------

**Learn more** ///  ///  /// More about how to delete electronic signature from document in Java: /// [How to delete eSignature from document with GroupDocs.Signature][] ///  ///  /// Advanced use cases of deleting document eSignatures: /// [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C] ///  ///  ///


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
[DeleteResult](../../com.groupdocs.signature.domain/deleteresult) - Returns DeleteResult [DeleteResult](../../com.groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.
### generateSignaturePreview(PreviewSignatureOptions previewOptions) {#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-}
```
public static void generateSignaturePreview(PreviewSignatureOptions previewOptions)
```


ينشئ معاينة للتوقيع بناءً على خيارات SignOptions المعطاة. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | معاينة التوقيع مع خيارات SignOptions المعطاة. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


تنفيذ واجهة IDisposable لتنظيف الموارد الداخلية

