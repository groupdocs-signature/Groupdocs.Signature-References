---
title: Signature class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents main class that controls document signing process."
type: docs
url: /python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Represents main class that controls document signing process.

Learn more about GroupDocs.Signature features:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

The Signature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Initializes a new Signature instance with a document provided as a stream. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Initializes a new [`Signature`](/signature/python-net/groupdocs.signature/signature/) instance with a document stream and load options. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Initializes a new [`Signature`](/signature/python-net/groupdocs.signature/signature/) instance with a document provided by a stream and optional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Initializes a new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature/) with a document stream, load options, and signature settings. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Initializes a new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature/) with a document provided by file path. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Initializes a new Signature instance with the document provided by file path and load options. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Initializes a new [`Signature`](/signature/python-net/groupdocs.signature/signature/) instance with the document provided by a file path and optional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Initializes a new instance of [`Signature`](/signature/python-net/groupdocs.signature/signature/) with a document provided by file path, load options, and signature settings. |

### Methods
| Method | Description |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Deletes the specified [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Deletes the provided list of signatures from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Deletes signatures of the specified type from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Deletes signatures of the specified `SignatureType` list from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Deletes a signature by its specific signature Id from the document. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Deletes the specified signatures from the document. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Cleans up internal resources used by the signature object. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Generates document pages preview. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Generates a signature preview based on the given SignOptions. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Gets information about document pages: their sizes, maximum page height, the width of a page with the maximum height. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Searches for signatures in a document using a list of [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Searches for signatures in the document using the provided search options and filters the results based on the specified predicate. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Searches for specified signature types in the document by `SignatureType` value. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Searches for signatures in the document using all available search options and filters the results based on the specified predicate. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves result to a stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Signs a document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to a stream using predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Signs document with a collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to a stream. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Signs document with a collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to a stream using predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Signs document with SignOptions and saves result to specified file path. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Signs document with [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves result to specified file path with predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Signs document with collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves result to specified file path. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Signs the document with a collection of [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) and saves the result to the specified file path using predefined [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/). |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Updates passed signature BaseSignature in the document. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Updates passed signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) in the document. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Verifies the document signatures with given VerifyOptions data. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Verifies the document signatures using the provided verification options and filters the results based on the specified predicate. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Verifies the document signatures with a list of VerifyOptions data. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Verifies document signatures using the provided verification options and filters the results with the given predicate. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Task guides that use `Signature`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### See Also
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
