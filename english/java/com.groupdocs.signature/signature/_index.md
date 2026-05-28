---
title: Signature
second_title: GroupDocs.Signature for Java API Reference
description: Represents main class that controls document signing process.
type: docs
weight: 10
url: /java/com.groupdocs.signature/signature/
---
**Inheritance:**
java.lang.Object
```
public class Signature
```

Represents main class that controls document signing process.

<br />

*** ** * ** ***

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](../https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

<br />


## Constructors

| Constructor | Description |
| --- | --- |
| [Signature(InputStream document)](#Signature-java.io.InputStream-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class with document provided by stream.
 |
| [Signature(InputStream document, LoadOptions loadOptions)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class with document provided by stream and load options 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
 |
| [Signature(InputStream document, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.SignatureSettings-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by stream and [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
 |
| [Signature(InputStream document, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.io.InputStream-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by stream, load options 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) and settings [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
 |
| [Signature(String filePath)](#Signature-java.lang.String-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path.
 |
| [Signature(String filePath, LoadOptions loadOptions)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path and 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).
 |
| [Signature(String filePath, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.SignatureSettings-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path and [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
 |
| [Signature(String filePath, LoadOptions loadOptions, SignatureSettings settings)](#Signature-java.lang.String-com.groupdocs.signature.options.loadoptions.LoadOptions-com.groupdocs.signature.SignatureSettings-) | Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path, 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) and [SignatureSettings](../../com.groupdocs.signature/signaturesettings).
 |
## Methods

| Method | Description |
| --- | --- |
| [sign(OutputStream document, SignOptions signOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-) | Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream.
 |
| [sign(OutputStream document, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.io.OutputStream-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).
 |
| [sign(OutputStream document, List<SignOptions> signOptionsList)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream.
 |
| [sign(OutputStream document, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.io.OutputStream-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).
 |
| [sign(String filePath, SignOptions signOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-) | Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path.
 |
| [sign(String filePath, SignOptions signOptions, SaveOptions saveOptions)](#sign-java.lang.String-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).
 |
| [sign(String filePath, List<SignOptions> signOptionsList)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--) | Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path.
 |
| [sign(String filePath, List<SignOptions> signOptionsList, SaveOptions saveOptions)](#sign-java.lang.String-java.util.List-com.groupdocs.signature.options.sign.SignOptions--com.groupdocs.signature.options.saveoptions.SaveOptions-) | Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).
 |
| [verify(VerifyOptions verifyOptions)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-) | Verifies the document signatures with given VerifyOptions data.
 |
| [verify(List<VerifyOptions> verifyOptionsList)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--) | Verifies the document signatures with list of VerifyOptions data.
 |
| [verify(VerifyOptions verifyOptions, Predicate<BaseSignature> predicate)](#verify-com.groupdocs.signature.options.verify.VerifyOptions-java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Verifies the document signatures using the provided verification options and filters
the succeeded results by the specified predicate.
 |
| [verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)](#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Verifies the document signatures using a list of verification options and filters the
succeeded results by the specified predicate.
 |
| [getDocumentInfo()](#getDocumentInfo--) | Gets information about document pages: their sizes,
maximum page height, the width of a page with the maximum height.
 |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.signature.options.preview.PreviewOptions-) | Generates document pages preview.
 |
| [search(List<SearchOptions> searchOptionsList)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--) | Searches for signatures in a document by [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) list.
 |
| [search(List<SearchOptions> searchOptionsList, Predicate<BaseSignature> predicate)](#search-java.util.List-com.groupdocs.signature.options.search.SearchOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--) | Searches for signatures by a list of options and filters the result by a predicate.
 |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-) | Searches for signatures in a document by [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) options.
 |
| [<T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)](#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--) | Searches for signatures of the specified type in the document, optionally filtered by a predicate.
 |
| [<T>search(Class<T> typeOfT, int signatureType)](#-T-search-java.lang.Class-T--int-) | Searches for exact type of signatures in the document by [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) value.
 |
| [search(int[] signatureTypes)](#search-int...-) | Searches for specified signature types in the document by [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) value.
 |
| [update(OutputStream document, BaseSignature signature)](#update-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Updates passed signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.
 |
| [update(OutputStream document, List<BaseSignature> signatures)](#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Updates passed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.
 |
| [update(String filePath, List<BaseSignature> signatures)](#update-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Updates passed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.
 |
| [update(String filePath, BaseSignature signature)](#update-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Updates passed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.
 |
| [delete(OutputStream document, BaseSignature signature)](#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-) | Deletes passed signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.
 |
| [delete(OutputStream document, List<BaseSignature> signatures)](#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Deletes passed list of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.
 |
| [delete(String filePath, BaseSignature signature)](#delete-java.lang.String-com.groupdocs.signature.domain.signatures.BaseSignature-) | Deletes passed signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.
 |
| [delete(String filePath, List<BaseSignature> signatures)](#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--) | Deletes passed list of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.
 |
| [delete(OutputStream document, int signatureType)](#delete-java.io.OutputStream-int-) | Deletes signatures of the certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
 |
| [deleteByTypes(OutputStream document, List<Integer> signatureTypes)](#deleteByTypes-java.io.OutputStream-java.util.List-java.lang.Integer--) | Deletes the signatures of the certain types list [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
 |
| [delete(String filePath, int signatureType)](#delete-java.lang.String-int-) | Deletes signatures of the certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
 |
| [deleteByTypes(String filePath, List<Integer> signatureTypes)](#deleteByTypes-java.lang.String-java.util.List-java.lang.Integer--) | Deletes the signatures of the certain types list [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
 |
| [delete(String signatureId)](#delete-java.lang.String-) | Deletes signature by its specific signature Id from the document.
 |
| [delete(List<String> signatureIds)](#delete-java.util.List-java.lang.String--) | Deletes passed list of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.
 |
| [generateSignaturePreview(PreviewSignatureOptions previewOptions)](#generateSignaturePreview-com.groupdocs.signature.options.PreviewSignatureOptions-) | Generates Signature preview based on given SignOptions.
 |
| [dispose()](#dispose--) | Implement IDisposable interface to clean up internal resources
 |
### Signature(InputStream document) {#Signature-java.io.InputStream-}
```
public Signature(InputStream document)
```


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class with document provided by stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The document content stream.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class with document provided by stream and load options 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The document content stream.
 |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | The document load options.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by stream and [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The document content stream.
 |
| settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | The signature settings.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by stream, load options 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) and settings [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The document content stream.
 |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | The document load options.
 |
| settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | The signature settings.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Absolute or relative file path.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path and 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Absolute or relative file path.
 |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | The document load options.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path and [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Absolute or relative file path.
 |
| settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | The signature settings.

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


Initializes new instance of [Signature](../../com.groupdocs.signature/signature) class instance with document provided by file path, 
LoadOptions
(#getLoadOptions.getLoadOptions/#setLoadOptions(LoadOptions).setLoadOptions(LoadOptions)) and [SignatureSettings](../../com.groupdocs.signature/signaturesettings).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Absolute or relative file path.
 |
| loadOptions | [LoadOptions](../../com.groupdocs.signature.options.loadoptions/loadoptions) | The document load options.
 |
| settings | [SignatureSettings](../../com.groupdocs.signature/signaturesettings) | The signature settings.

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


Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | The signature options.

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


Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | The signature options.
 |
| saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | The save options.

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


Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | The list of signature options.

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


Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to a stream with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | The list of signature options.
 |
| saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | The save options.

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


Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | The signature options.

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


Signs document with [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | The signature options.
 |
| saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | The save options.

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


Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | The list of signature options.

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


Signs document with collection of [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) and saves result to specified file path with predefined [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signOptionsList | java.util.List<com.groupdocs.signature.options.sign.SignOptions> | The list of signature options.
 |
| saveOptions | [SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions) | The save options.

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


Verifies the document signatures with given VerifyOptions data.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | The signature verification options.

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


Verifies the document signatures with list of VerifyOptions data.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | The signature verification options collection. Instance of [VerifyOptionsCollection](../../com.groupdocs.signature.options.verify/verifyoptionscollection).

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


Verifies the document signatures using the provided verification options and filters
the succeeded results by the specified predicate.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptions | [VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions) | The signature verification options.
 |
| predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Filter predicate applied on the list of verified signatures.
 |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - List of signatures that succeeded verification and satisfied the predicate.

### verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate) {#verify-java.util.List-com.groupdocs.signature.options.verify.VerifyOptions--java.util.function.Predicate-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final List<BaseSignature> verify(List<VerifyOptions> verifyOptionsList, Predicate<BaseSignature> predicate)
```


Verifies the document signatures using a list of verification options and filters the
succeeded results by the specified predicate.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| verifyOptionsList | java.util.List<com.groupdocs.signature.options.verify.VerifyOptions> | The signature verification options list.
 |
| predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Filter predicate applied on the list of verified signatures.
 |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> - List of signatures that succeeded verification and satisfied the predicate.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets information about document pages: their sizes,
maximum page height, the width of a page with the maximum height.


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


Generates document pages preview.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.signature.options.preview/previewoptions) | The preview options.

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


Searches for signatures in a document by [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) list.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | The search options collection.

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


Searches for signatures by a list of options and filters the result by a predicate.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| searchOptionsList | java.util.List<com.groupdocs.signature.options.search.SearchOptions> | The list of search options.
 |
| predicate | java.util.function.Predicate<com.groupdocs.signature.domain.signatures.BaseSignature> | Predicate used to filter the resulting signatures.
 |

**Returns:**
[SearchResult](../../com.groupdocs.signature.domain/searchresult) - SearchResult containing only signatures that match the predicate.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions)
```


Searches for signatures in a document by [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) options.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | The search options.

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

 |

**Returns:**
java.util.List<T> - Returns the list of signatures found.

### <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate) {#-T-search-java.lang.Class-T--com.groupdocs.signature.options.search.SearchOptions-java.util.function.Predicate-T--}
```
public final List<T> <T>search(Class<T> typeOfT, SearchOptions searchOptions, Predicate<T> predicate)
```


Searches for signatures of the specified type in the document, optionally filtered by a predicate.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> | Generic type parameter of [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
 |
| searchOptions | [SearchOptions](../../com.groupdocs.signature.options.search/searchoptions) | Options for signature search.
 |
| predicate | java.util.function.Predicate<T> | Optional predicate filter applied after the search. May be  null .
 |

**Returns:**
java.util.List<T> - List of found signatures, optionally filtered by the predicate.

### <T>search(Class<T> typeOfT, int signatureType) {#-T-search-java.lang.Class-T--int-}
```
public final List<T> <T>search(Class<T> typeOfT, int signatureType)
```


Searches for exact type of signatures in the document by [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) value.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| signatureType | int | The type of signatures to search.

<br />

*** ** * ** ***

**Learn more**

* More about search electronic signatures in a documents using GroupDocs.Signature: [How to search for electronic signatures inside document using Java](../https://docs.groupdocs.com/signature/java/search-for-electronic-signatures-in-document/)
* More about electronic signatures search dependent on eSign type: [Advanced use cases of electronic signatures search with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/searching/)

<br />

 |

**Returns:**
java.util.List<T> - Returns the list of found signatures with exact type.

### search(int[] signatureTypes) {#search-int...-}
```
public final SearchResult search(int[] signatureTypes)
```


Searches for specified signature types in the document by [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) value.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureTypes | int[] | One or several types of signatures to find.

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


Updates passed signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signature object to be updated in the document.

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

 |

**Returns:**
boolean - Returns true if operation was successful.

### update(OutputStream document, List<BaseSignature> signatures) {#update-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final UpdateResult update(OutputStream document, List<BaseSignature> signatures)
```


Updates passed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | List of signatures to update in the document.

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


Updates passed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | List of signatures to update in the document.

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


Updates passed signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) in the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signature object to be updated in the document.

<br />

*** ** * ** ***

**Learn more**

* More about how to update existing electronic signature properties using GroupDocs.Signature: [How to update document eSignatures in Java](../https://docs.groupdocs.com/signature/java/update-signatures-in-documents/)
* More advanced use cases of updating document electronic signatures dependent on signature type: [Advanced use cases of electronic signatures update with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/updating/)

<br />

 |

**Returns:**
boolean - Returns UpdateResult [UpdateResult](../../com.groupdocs.signature.domain/updateresult) with list of successfully updated signatures and failed ones.

### delete(OutputStream document, BaseSignature signature) {#delete-java.io.OutputStream-com.groupdocs.signature.domain.signatures.BaseSignature-}
```
public final boolean delete(OutputStream document, BaseSignature signature)
```


Deletes passed signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signature object to be removed from the document.

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

 |

**Returns:**
boolean - Returns true if operation was successful.

### delete(OutputStream document, List<BaseSignature> signatures) {#delete-java.io.OutputStream-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(OutputStream document, List<BaseSignature> signatures)
```


Deletes passed list of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | List of signatures to remove from the document.

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


Deletes passed signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signature | [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) | Signature object to be removed from the document.

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/delete-signatures-from-documents/)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in Java](../https://docs.groupdocs.com/signature/java/deleting/)

<br />

 |

**Returns:**
boolean - Returns true if operation was successful.

### delete(String filePath, List<BaseSignature> signatures) {#delete-java.lang.String-java.util.List-com.groupdocs.signature.domain.signatures.BaseSignature--}
```
public final DeleteResult delete(String filePath, List<BaseSignature> signatures)
```


Deletes passed list of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signatures | java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature> | List of signatures to remove from the document.

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


Deletes signatures of the certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
Only signatures that were added by Sign method and marked as Signatures 
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) will be removed.
Following signature types are supported: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signatureType | int | The type of signatures to be removed from the document.

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


Deletes the signatures of the certain types list [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
Only signatures that were added by Sign method and marked as Signatures 
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) will be removed.
Following signature types are supported: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The output document stream.
 |
| signatureTypes | java.util.List<java.lang.Integer> | The list of signatures types to be removed from the document.

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


Deletes signatures of the certain type [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
Only signatures that were added by Sign method and marked as Signatures 
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) will be removed.
Following signature types are supported: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signatureType | int | The type of signatures to be removed from the document.

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


Deletes the signatures of the certain types list [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) from the document.
Only signatures that were added by Sign method and marked as Signatures 
BaseSignature.isSignature()
([BaseSignature.isSignature](../../com.groupdocs.signature.domain.signatures/basesignature#isSignature)/[BaseSignature.setSignature(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setSignature-boolean-)) will be removed.
Following signature types are supported: Text, Image, Digital, Barcode, QR-Code


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The output file path.
 |
| signatureTypes | java.util.List<java.lang.Integer> | The list of signatures types to be removed from the document.

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


Deletes signature by its specific signature Id from the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String | The Id of the signature to be removed from the document.

<br />

*** ** * ** ***

**Learn more**

* More about how to delete electronic signature from document in Java: [How to delete eSignature from document with GroupDocs.Signature](../https://docs.groupdocs.com/signature/java/Delete+signatures+from+documents)
* Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](../https://docs.groupdocs.com/signature/java/Deleting)

<br />

 |

**Returns:**
boolean - Returns true if operation was successful.

### delete(List<String> signatureIds) {#delete-java.util.List-java.lang.String--}
```
public final DeleteResult delete(List<String> signatureIds)
```


Deletes passed list of signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) from the document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureIds | java.util.List<java.lang.String> | List of the identifiers of the signatures to be removed from the document.

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


Generates Signature preview based on given SignOptions. [SignOptions](../../com.groupdocs.signature.options.sign/signoptions)


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions) | The preview signature with given SignOptions. [PreviewSignatureOptions](../../com.groupdocs.signature.options/previewsignatureoptions)

<br />

*** ** * ** ***

**Learn more**

* Learn more about how to generate previews of the signatures:
 |

### dispose() {#dispose--}
```
public final void dispose()
```


Implement IDisposable interface to clean up internal resources


