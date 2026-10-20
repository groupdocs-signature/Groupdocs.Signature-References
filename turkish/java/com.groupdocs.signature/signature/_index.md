---
title: "Signature"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "Belge imzalama sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Belge imzalama sürecini kontrol eden ana sınıfı temsil eder.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Signature(InputStream document)](#Signature-java.io.InputStream-) | Akış tarafından sağlanan belgeyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Akış tarafından sağlanan belge ve yükleme seçenekleriyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Akış tarafından sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır. |
|
|  | [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Akış tarafından sağlanan belge, yükleme seçenekleriyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve ayarlar [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
|  | [Signature(String filePath)](#Signature-java.lang.String-) | Dosya yolu ile sağlanan belgeyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır. |
|
|  | [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Dosya yolu ile sağlanan belge ve |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
|
|  | [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Dosya yolu ile sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır. |
|
|  | [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Dosya yolu ile sağlanan belgeyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır, |
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu bir akışa kaydeder. |
|
|  | [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile bir akışa kaydeder. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu bir akışa kaydeder. |
|
|  | [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile bir akışa kaydeder. |
|
|  | [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
|
|  | [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu belirtilen dosya yoluna önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile kaydeder. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu belirtilen dosya yoluna kaydeder. |
|
|  | [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu belirtilen dosya yoluna önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile kaydeder. |
|
|  | [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Verilen VerifyOptions verileriyle belge imzalarını doğrular. |
|
|  | [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | VerifyOptions verileri listesini kullanarak belge imzalarını doğrular. |
|
|  | [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Sağlanan doğrulama seçeneklerini ve filtreleri kullanarak belge imzalarını doğrular |
belirtilen koşula göre başarılı sonuçlar.
|
|  | [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Doğrulama seçenekleri listesini kullanarak belge imzalarını doğrular ve filtreler |
başarılı sonuçları belirtilen koşula göre.
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Belge sayfaları hakkında bilgi alır: boyutları, |
maksimum sayfa yüksekliği, maksimum yüksekliğe sahip bir sayfanın genişliği.
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Belge sayfalarının önizlemesini oluşturur. |
|
|  | [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Bir belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) listesiyle arar. |
|
|  | [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | İmzaları bir seçenek listesiyle arar ve sonucu bir koşula göre filtreler. |
|
|  | [search(Predicate<BaseSignature> predicate)](#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgeyi tüm tipteki imzalar (metin, resim, dijital, barkod, QR-kod ve meta veri) için arar |
ve onları bir koşula göre filtreler.
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Bir belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) seçenekleriyle arar. |
|
|  | [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Belgedeki belirtilen tipteki imzaları arar, isteğe bağlı olarak bir koşula göre filtrelenir. |
|
|  | [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Belgedeki imzaların kesin tipini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar. |
|
|  | [search(int[] signatureTypes)](#search-int...-) | Belgedeki belirtilen imza tiplerini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar. |
|
|  | [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgedeki verilen imza [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller. |
|
|  | [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgedeki verilen imzalar [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller. |
|
|  | [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgedeki verilen imzalar [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller. |
|
|  | [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgedeki verilen imzalar [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller. |
|
|  | [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgeden verilen imza [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler. |
|
|  | [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgeden verilen imza listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler. |
|
|  | [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Belgeden verilen imza [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler. |
|
|  | [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Belgeden verilen imza listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler. |
|
|  | [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Belgeden belirli tipteki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. |
|
|  | [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Belgeden belirli tipteki imzaların listesini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. |
|
|  | [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Belgeden belirli tipteki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. |
|
|  | [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Belgeden belirli tipteki imzaların listesini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler. |
|
|  | [delete(String signatureId)](#delete-java.lang.String-) | Belgeden belirli imza kimliğiyle imzayı siler. |
|
|  | [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Belgeden verilen imza listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler. |
|
|  | [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Verilen SignOptions temelinde İmza önizlemesi oluşturur. |
|
|  | [dispose()](#dispose--) | İç kaynakları temizlemek için IDisposable arabirimini uygulayın |
|
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Akış tarafından sağlanan belgeyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içerik akışı. |

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


Akış tarafından sağlanan belge ve yükleme seçenekleriyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içerik akışı. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |

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


Akış tarafından sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içerik akışı. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


Akış tarafından sağlanan belge, yükleme seçenekleriyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve ayarlar [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belge içerik akışı. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


Dosya yolu ile sağlanan belgeyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |

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


Dosya yolu ile sağlanan belge ve
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |

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


Dosya yolu ile sağlanan belge ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings) ile [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


Dosya yolu ile sağlanan belgeyle [Signature](../../com.groupdocs.signature/signature) sınıfının yeni bir örneğini başlatır,
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) ve [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Mutlak veya göreceli dosya yolu. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | Belge yükleme seçenekleri. |
|
|  | settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | İmza ayarları. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu bir akışa kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile bir akışa kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu bir akışa kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile bir akışa kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu belirtilen dosya yoluna kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) ile belgeyi imzalar ve sonucu belirtilen dosya yoluna önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | İmza seçenekleri. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu belirtilen dosya yoluna kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |

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


[SignOptions](../../com.groupdocs.signature.options.sign/signoptions) koleksiyonu ile belgeyi imzalar ve sonucu belirtilen dosya yoluna önceden tanımlı [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) ile kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | İmza seçenekleri listesi. |
|
|  | saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | Kaydetme seçenekleri. |

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


Verilen VerifyOptions verileriyle belge imzalarını doğrular.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | İmza doğrulama seçenekleri. |

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


VerifyOptions verileri listesini kullanarak belge imzalarını doğrular.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | İmza doğrulama seçenekleri koleksiyonu. [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection) örneği. |

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


Sağlanan doğrulama seçeneklerini ve filtreleri kullanarak belge imzalarını doğrular
belirtilen koşula göre başarılı sonuçlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | İmza doğrulama seçenekleri. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Doğrulanmış imzalar listesine uygulanan filtre koşulu. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Doğrulama başarılı olan ve koşulu sağlayan imzaların listesi.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Doğrulama seçenekleri listesini kullanarak belge imzalarını doğrular ve filtreler
başarılı sonuçları belirtilen koşula göre.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | İmza doğrulama seçenekleri listesi. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Doğrulanmış imzalar listesine uygulanan filtre koşulu. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Doğrulama başarılı olan ve koşulu sağlayan imzaların listesi.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Belge sayfaları hakkında bilgi alır: boyutları,
maksimum sayfa yüksekliği, maksimum yüksekliğe sahip bir sayfanın genişliği.


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


Belge sayfalarının önizlemesini oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | Önizleme seçenekleri. |

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


Bir belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) listesiyle arar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Arama seçenekleri koleksiyonu. |

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


İmzaları bir seçenek listesiyle arar ve sonucu bir koşula göre filtreler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | Arama seçeneklerinin listesi. |
|
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Sonuç imzalarını filtrelemek için kullanılan Predicate. |
|

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### search(Predicate<BaseSignature> predicate) {#search-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> search(Predicate<BaseSignature> predicate)
```


Belgeyi tüm tipteki imzalar (metin, resim, dijital, barkod, QR-kod ve meta veri) için arar
ve onları bir koşula göre filtreler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Bulunan imzaların listesine uygulanacak filtre Predicate'i. |
|

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - Sağlanan predicate'i karşılayan [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) örneklerinin bir listesini döndürür.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Bir belgede imzaları [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) seçenekleriyle arar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Arama seçenekleri. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Bulunan imzaların listesini döndürür.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Belgedeki belirtilen tipteki imzaları arar, isteğe bağlı olarak bir koşula göre filtrelenir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | typeOfT | java.lang.Class<T> | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) için genel tip parametresi. |
|
|  | searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | İmza araması için seçenekler. |
|
|  | predicate | java.util.function.Predicate<T> | Aramadan sonra uygulanan isteğe bağlı predicate filtresi. Null olabilir. |
|

**Returns:**
java.util.List<T> - Bulunan imzaların listesi, isteğe bağlı olarak predicate ile filtrelenmiş.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Belgedeki imzaların kesin tipini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | signatureType | int | Aranacak imzaların tipi. |

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

|

**Returns:**
java.util.List<T> - Tam tipiyle bulunan imzaların listesini döndürür.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Belgedeki belirtilen imza tiplerini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) değeriyle arar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureTypes | int[] | Bulunacak bir veya birden fazla imza tipi. |

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


Belgedeki verilen imza [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgede güncellenecek imza nesnesi. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - İşlem başarılıysa true döndürür.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Belgedeki verilen imzalar [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgede güncellenecek imzaların listesi. |

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


Belgedeki verilen imzalar [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgede güncellenecek imzaların listesi. |

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


Belgedeki verilen imzalar [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgede güncellenecek imza nesnesi. |

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

|

**Returns:**
boolean - Başarıyla güncellenen ve başarısız olan imzaların listesiyle birlikte UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) döndürür.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Belgeden verilen imza [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgeden kaldırılacak imza nesnesi. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - İşlem başarılıysa true döndürür.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Belgeden verilen imza listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgeden kaldırılacak imzaların listesi. |

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


Belgeden verilen imza [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Belgeden kaldırılacak imza nesnesi. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

|

**Returns:**
boolean - İşlem başarılıysa true döndürür.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Belgeden verilen imza listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | Belgeden kaldırılacak imzaların listesi. |

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


Belgeden belirli tipteki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler.
Yalnızca Sign yöntemiyle eklenen ve Signatures olarak işaretlenen imzalar
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) kaldırılacak.
Aşağıdaki imza türleri desteklenir: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signatureType | int | Belgeden kaldırılacak imzaların türü. |

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


Belgeden belirli tipteki imzaların listesini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler.
Yalnızca Sign yöntemiyle eklenen ve Signatures olarak işaretlenen imzalar
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) kaldırılacak.
Aşağıdaki imza türleri desteklenir: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Çıktı belge akışı. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Belgeden kaldırılacak imza türlerinin listesi. |

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


Belgeden belirli tipteki imzaları [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler.
Yalnızca Sign yöntemiyle eklenen ve Signatures olarak işaretlenen imzalar
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) kaldırılacak.
Aşağıdaki imza türleri desteklenir: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signatureType | int | Belgeden kaldırılacak imzaların türü. |

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


Belgeden belirli tipteki imzaların listesini [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) siler.
Yalnızca Sign yöntemiyle eklenen ve Signatures olarak işaretlenen imzalar
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) kaldırılacak.
Aşağıdaki imza türleri desteklenir: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Çıktı dosya yolu. |
|
|  | signatureTypes | java.util.List<java.lang.Integer> | Belgeden kaldırılacak imza türlerinin listesi. |

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


Belgeden belirli imza kimliğiyle imzayı siler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureId | java.lang.String | Belgeden kaldırılacak imzanın kimliği. |

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

|

**Returns:**
boolean - İşlem başarılıysa true döndürür.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Belgeden verilen imza listesi [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) siler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | signatureIds | java.util.List<java.lang.String> | Belgeden kaldırılacak imzaların tanımlayıcılarının listesi. |

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


Verilen SignOptions temelinde İmza önizlemesi oluşturur. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | Verilen SignOptions ile önizleme imzası. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) |

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
|

### dispose() {#dispose--}
```
public final void dispose()
```


İç kaynakları temizlemek için IDisposable arabirimini uygulayın


