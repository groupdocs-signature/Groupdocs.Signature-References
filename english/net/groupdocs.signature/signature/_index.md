---
title: Signature
second_title: GroupDocs.Signature for .NET API Reference
description: Represents main class that controls document signing process.
type: docs
weight: 2110
url: /net/groupdocs.signature/signature/
---
## Signature class

Represents main class that controls document signing process.

```csharp
public class Signature : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [Signature](signature#constructor)(Stream) | Initializes new instance of [`Signature`](../signature) class with document provided by stream. |
| [Signature](signature#constructor_4)(string) | Initializes new instance of [`Signature`](../signature) class instance with document provided by file path. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | Initializes new instance of [`Signature`](../signature) class with document provided by stream and load options LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | Initializes new instance of [`Signature`](../signature) class instance with document provided by stream and [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | Initializes new instance of [`Signature`](../signature) class instance with document provided by file path and LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | Initializes new instance of [`Signature`](../signature) class instance with document provided by file path and [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | Initializes new instance of [`Signature`](../signature) class instance with document provided by stream, load options LoadOptions and settings [`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | Initializes new instance of [`Signature`](../signature) class instance with document provided by file path, LoadOptions and [`SignatureSettings`](../signaturesettings). |

## Methods

| Name | Description |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | Deletes passed signature [`BaseSignature`](../../groupdocs.signature.domain/basesignature) from the document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | Deletes passed list of signatures [`BaseSignature`](../../groupdocs.signature.domain/basesignature) from the document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | Deletes the signatures of the certain types list [`SignatureType`](../../groupdocs.signature.domain/signaturetype) from the document. Only signatures that were added by Sign method and marked as Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) will be removed. Following signature types are supported: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | Deletes passed list of signatures [`BaseSignature`](../../groupdocs.signature.domain/basesignature) from the document. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | Deletes signatures of the certain type [`SignatureType`](../../groupdocs.signature.domain/signaturetype) from the document. Only signatures that were added by Sign method and marked as Signatures [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) will be removed. Following signature types are supported: Text, Image, Digital, Barcode, QR-Code |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | Deletes signature by its specific signature Id from the document. |
| [Dispose](../../groupdocs.signature/signature/dispose)() | Implement IDisposable interface to clean up internal resources |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | Generates document pages preview. |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height. |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | Searches for signatures in the document using all available search options and filters the results based on the specified predicate. |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | Searches for signatures in a document by [`SearchOptions`](../../groupdocs.signature.options/searchoptions) list. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | Searches for specified signature types in the document by [`SignatureType`](../../groupdocs.signature.domain/signaturetype) value. |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Searches for signatures in the document using the provided search options and filters the results based on the specified predicate. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | Searches for signatures in a document by [`SearchOptions`](../../groupdocs.signature.options/searchoptions) options. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | Searches for exact type of signatures in the document by [`SignatureType`](../../groupdocs.signature.domain/signaturetype) value. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_6)(SearchOptions, Func&lt;T, bool&gt;) | Searches for signatures in the document using the provided search options and filters the results based on the specified predicate. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | Signs document with collection of [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to a stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | Signs document with [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to a stream. |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | Signs document with collection of [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to specified file path. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | Signs document with [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to specified file path. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | Signs document with collection of [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to a stream with predefined [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | Signs document with [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to a stream with predefined [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | Signs document with collection of [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to specified file path with predefined [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | Signs document with [`SignOptions`](../../groupdocs.signature.options/signoptions) and saves result to specified file path with predefined [`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | Updates passed signature [`BaseSignature`](../../groupdocs.signature.domain/basesignature) in the document. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | Updates passed signatures [`BaseSignature`](../../groupdocs.signature.domain/basesignature) in the document. |
| [Verify](../../groupdocs.signature/signature/verify#verify_4)(Func&lt;BaseSignature, bool&gt;) | Verifies the document signatures using all available verification options and filters the results based on the specified predicate. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | Verifies the document signatures with list of VerifyOptions data. |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | Verifies the document signatures with given VerifyOptions data. |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | Verifies the document signatures using all available verification options and filters the results based on the specified predicate. |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | Verifies the document signatures using the provided verification options and filters the results based on the specified predicate. |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | Generates Signature preview based on given SignOptions. [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## Events

| Name | Description |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | Occurs when signature search process completed. |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | Occurs when signature search process progress changed. |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | Occurs when signature search process started. |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | Occurs when document signing process completed. |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | Occurs when document signing process progress changed. |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | Occurs when document signing process started. |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | Occurs when signature verification process completed. |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | Occurs when signature verification process progress changed. |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | Occurs when signature verification process started. |

### Remarks

**Learn more**

* More about GroupDocs.Signature features: [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### See Also

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
