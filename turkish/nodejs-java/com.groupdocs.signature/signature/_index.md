---
title: "İmza"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Belge imzalama sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Belge imzalama sürecini kontrol eden ana sınıfı temsil eder.

--------------------

**Learn more**

 *  More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide][]


[GroupDocs.Signature Developer Guide]: https://docs.groupdocs.com/display/signaturenet/Developer+Guide
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belgeyle başlatır. |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belge ve yükleme seçenekleri LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ile başlatır. |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır. |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belge, yükleme seçenekleri LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve ayarlar [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır. |
| [Signature(String filePath)](#Signature-java.lang.String-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belgeyle başlatır. |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belge ve  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ile başlatır. |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır. |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belge,  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve sonucu bir akışa kaydeder. |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu bir akışa kaydeder. |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve sonucu bir akışa kaydeder. |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu bir akışa kaydeder. |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu belirtilen dosya yoluna kaydeder. |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu belirtilen dosya yoluna kaydeder. |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Belge imzalarını verilen VerifyOptions verileriyle doğrular. |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Belge imzalarını VerifyOptions veri listesiyle doğrular. |
| [getDocumentInfo()](#getDocumentInfo--) | Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Belge sayfalarının önizlemesini oluşturur. |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) listesiyle arar. |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) seçenekleriyle arar. |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Belgedeki imzaların tam türünü [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar. |
| [search(int[] signatureTypes)](#search-int...-) | Belgedeki belirtilen imza türlerini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar. |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzasını günceller. |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzalarını günceller. |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzalarını günceller. |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzalarını günceller. |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzasını siler. |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imza listesini siler. |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzasını siler. |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imza listesini siler. |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Belgeden belirli bir türdeki [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) imzalarını siler. |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Belgeden belirli türler listesindeki [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) imzalarını siler. |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Belgeden belirli bir türdeki [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) imzalarını siler. |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Belgeden belirli türler listesindeki [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) imzalarını siler. |
| [delete(String signatureId)](#delete-java.lang.String-) | Belgeden belirli imza kimliğiyle imzayı siler. |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imza listesini siler. |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Verilen SignOptions temelinde İmza önizlemesi oluşturur. |
| [dispose()](#dispose--) | İç kaynakları temizlemek için IDisposable arayüzünü uygula. |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belgeyle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içerik akışı. |

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


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belge ve yükleme seçenekleri LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Belge içerik akışı. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |

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


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Belge içerik akışı. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini akış tarafından sağlanan belge, yükleme seçenekleri LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve ayarlar [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.InputStream | Belge içerik akışı. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belgeyle başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |

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


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belge ve  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |

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


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

--------------------

 **Learn more** 

 *  
 *   |

### Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings) {#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-}
```
public Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)
```


[Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini dosya yolu ile sağlanan belge,  LoadOptions (\#getLoadOptions.getLoadOptions/\#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve sonucu bir akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu bir akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve sonucu bir akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu bir akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve sonucu belirtilen dosya yoluna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu belirtilen dosya yoluna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve sonucu belirtilen dosya yoluna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |

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


Belgeyi [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile imzalar ve önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile sonucu belirtilen dosya yoluna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


Belge imzalarını verilen VerifyOptions verileriyle doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | İmza doğrulama seçenekleri. |

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


Belge imzalarını VerifyOptions veri listesiyle doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | İmza doğrulama seçenekleri koleksiyonu. Örneği [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection). |

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


Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip sayfanın genişliği.

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


Belge sayfalarının önizlemesini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Ön izleme seçenekleri. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Signature][]


[How to generate document pages preview using GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/generate-document-pages-preview/ |

### search(List<SearchOptions> searchOptionsList) {#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--}
```
public final SearchResult search(List<SearchOptions> searchOptionsList)
```


Belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) listesiyle arar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Arama seçenekleri koleksiyonu. |

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


Belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) seçenekleriyle arar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Arama seçenekleri. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Bulunan imzaların listesini döndürür.
### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Belgedeki imzaların tam türünü [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Aranacak imza türü. |

--------------------

**Learn more**

 *  More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java][]
 *  More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature][]


[How to search for electronic signatures inside document using Java]: https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/
[Advanced use cases of electronic signatures search with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/searching/ |

**Returns:**
java.util.List<T> - Tam türüyle bulunan imzaların listesini döndürür.
### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Belgedeki belirtilen imza türlerini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureTypes | int[] | Bulmak için bir veya birkaç imza türü. |

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


Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzasını günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgede güncellenecek imza nesnesi. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - İşlem başarılıysa true döndürür.
### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzalarını günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | imzalar | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgede güncellenecek imzaların listesi. |

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


Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzalarını günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | imzalar | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgede güncellenecek imzaların listesi. |

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


Belgedeki verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzalarını günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgede güncellenecek imza nesnesi. |

--------------------

**Learn more**

 *  More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java][]
 *  More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature][]


[How to update document eSignatures in Java]: https://docs.groupdocs.com/signature/java/update-signatures-in-documents/
[Advanced use cases of electronic signatures update with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/updating/ |

**Returns:**
boolean - Başarıyla güncellenen imzalar ve başarısız olanların listesiyle birlikte UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) döndürür.
### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzasını siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgeden kaldırılacak imza nesnesi. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - İşlem başarılıysa true döndürür.
### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imza listesini siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | imzalar | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgeden kaldırılacak imzaların listesi. |

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


Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imzasını siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgeden kaldırılacak imza nesnesi. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java][]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/
[How to delete different types of eSignatures from document in Java]: https://docs.groupdocs.com/signature/java/deleting/ |

**Returns:**
boolean - İşlem başarılıysa true döndürür.
### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imza listesini siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | imzalar | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgeden kaldırılacak imzaların listesi. |

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


Belgeden belirli bir türdeki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. Yalnızca Sign yöntemiyle eklenen ve Imzalar olarak işaretlenen BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) imzaları kaldırılacaktır. Desteklenen imza türleri şunlardır: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | signatureType | int | Belgeden kaldırılacak imzaların türü. |

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


Belgeden belirli türler listesindeki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. Yalnızca Sign yöntemiyle eklenen ve Imzalar olarak işaretlenen BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) imzaları kaldırılacaktır. Desteklenen imza türleri şunlardır: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | java.io.OutputStream | Çıktı belge akışı. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Belgeden kaldırılacak imza türlerinin listesi. |

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


Belgeden belirli bir türdeki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. Yalnızca Sign yöntemiyle eklenen ve Imzalar olarak işaretlenen BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) imzaları kaldırılacaktır. Desteklenen imza türleri şunlardır: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | signatureType | int | Belgeden kaldırılacak imzaların türü. |

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


Belgeden belirli türler listesindeki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. Yalnızca Sign yöntemiyle eklenen ve Imzalar olarak işaretlenen BaseSignature.isSignature() ([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature\#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature\#setSignature-boolean-)) imzaları kaldırılacaktır. Desteklenen imza türleri şunlardır: Text, Image, Digital, Barcode, QR-Code

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Çıktı dosya yolu. |
|  | signatureTypes | java.util.List<java.lang.Integer> | Belgeden kaldırılacak imza türlerinin listesi. |

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


Belgeden belirli imza kimliğiyle imzayı siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureId | java.lang.String | Belgeden kaldırılacak imzanın Id'si. |

--------------------

**Learn more**

 *  More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature][]
 *  Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C\#][How to delete different types of eSignatures from document in C]


[How to delete eSignature from document with GroupDocs.Signature]: https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents
[How to delete different types of eSignatures from document in C]: https://docs.groupdocs.com/signature/java/Deleting |

**Returns:**
boolean - İşlem başarılıysa true döndürür.
### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Belgeden verilen [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) imza listesini siler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Belgeden kaldırılacak imzaların tanımlayıcılarının listesi. |

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


Verilen SignOptions temelinde İmza önizlemesi oluşturur. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Verilen SignOptions ile önizleme imzası. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

--------------------

**Learn more**

 *  Learn more about how to generate previews of the signatures: |

### dispose() {#dispose--}
```
public final void dispose()
```


İç kaynakları temizlemek için IDisposable arayüzünü uygula.

