---
title: Signature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signature/
is_root: false
weight: 100
---

## Signature class

Represents main class that controls document signing process.



The Signature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#io.RawIOBase) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class with document provided by stream. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#io.RawIOBase-groupdocs.signature.options.LoadOptions) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class with document provided by stream and load options [`Signature.LoadOptions`](/signature/python-net/groupdocs.signature/signature). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#io.RawIOBase-groupdocs.signature.SignatureSettings) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class instance with document provided by stream and [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#io.RawIOBase-groupdocs.signature.options.LoadOptions-groupdocs.signature.SignatureSettings) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class instance with document provided by stream, load options [`Signature.LoadOptions`](/signature/python-net/groupdocs.signature/signature) and settings [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#str) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class instance with document provided by file path. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#str-groupdocs.signature.options.LoadOptions) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class instance with document provided by file path and [`Signature.LoadOptions`](/signature/python-net/groupdocs.signature/signature). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#str-groupdocs.signature.SignatureSettings) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class instance with document provided by file path and [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#str-groupdocs.signature.options.LoadOptions-groupdocs.signature.SignatureSettings) | Initializes new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature) class instance with document provided by file path, [`Signature.LoadOptions`](/signature/python-net/groupdocs.signature/signature) and [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings). |


### Methods
| Method | Description |
| :- | :- |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#io.RawIOBase-groupdocs.signature.options.SignOptions) | Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to a stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#io.RawIOBase-groupdocs.signature.options.SignOptions-groupdocs.signature.options.SaveOptions) | Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to a stream with predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#io.RawIOBase-System.Collections.Generic.List<GroupDocs.Signature.Options.SignOptions>) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#io.RawIOBase-System.Collections.Generic.List<GroupDocs.Signature.Options.SignOptions>-groupdocs.signature.options.SaveOptions) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#str-groupdocs.signature.options.SignOptions) | Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to specified file path. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#str-groupdocs.signature.options.SignOptions-groupdocs.signature.options.SaveOptions) | Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) and saves result to specified file path with predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#str-System.Collections.Generic.List<GroupDocs.Signature.Options.SignOptions>) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#str-System.Collections.Generic.List<GroupDocs.Signature.Options.SignOptions>-groupdocs.signature.options.SaveOptions) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#groupdocs.signature.options.VerifyOptions) | Verifies the document signatures with given VerifyOptions data. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#System.Collections.Generic.List<GroupDocs.Signature.Options.VerifyOptions>) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#System.Collections.Generic.List<GroupDocs.Signature.Options.SearchOptions>) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#list) | Searches for specified signature types in the document by [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) value. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#groupdocs.signature.domain.BaseSignature) | Updates passed signature [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature) in the document. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#System.Collections.Generic.List<GroupDocs.Signature.Domain.BaseSignature>) |  |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#groupdocs.signature.domain.BaseSignature) | Deletes passed signature [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature) from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#System.Collections.Generic.List<GroupDocs.Signature.Domain.BaseSignature>) |  |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#groupdocs.signature.domain.SignatureType) | Deletes signatures of the certain type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) from the document.<br/>Only signatures that were added by Sign method and marked as Signatures [`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature#is_signature)  will be removed.<br/>Following signature types are supported: Text, Image, Digital, Barcode, QR-Code |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#System.Collections.Generic.List<GroupDocs.Signature.Domain.SignatureType>) |  |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#str) | Deletes signature by its specific signature Id from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#System.Collections.Generic.List<string>) |  |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/#) | Gets information about document pages: their sizes,<br/>maximum page height, the width of a page with the maximum height. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#groupdocs.signature.options.PreviewOptions) | Generates document pages preview. |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#groupdocs.signature.options.PreviewSignatureOptions) | Generates Signature preview based on given SignOptions. [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions) |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.signature`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`Signature`](/signature/python-net/groupdocs.signature/signature)
* class [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
