---
title: MetadataSignOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/metadatasignoptions/
is_root: false
weight: 230
---

## MetadataSignOptions class

Represents Metadata signature options.



**Inheritance:** [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions) → 
[`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)



The MetadataSignOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#) | Initializes a new instance of the MetadataSignOptions class with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasignoptions/__init__/#list) | Constructs a new instance of MetadataSignOptions |


### Properties
| Property | Description |
| :- | :- |
| [page_number](/signature/python-net/groupdocs.signature.options/metadatasignoptions/page_number) | Gets or sets document page number for signing.<br/>Minimal and default value is 1. |
| [all_pages](/signature/python-net/groupdocs.signature.options/metadatasignoptions/all_pages) | Put signature on all document pages. |
| [appearance](/signature/python-net/groupdocs.signature.options/metadatasignoptions/appearance) | Additional signature appearance. |
| [extensions](/signature/python-net/groupdocs.signature.options/metadatasignoptions/extensions) | Signature Extensions. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/metadatasignoptions/pages_setup) | Options to specify pages to be signed. |
| [signature_type](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signature_type) | Get the Signature Type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) |
| [document_type](/signature/python-net/groupdocs.signature.options/metadatasignoptions/document_type) | Get or set the Document Type of the Signature Options [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype) |
| [z_order](/signature/python-net/groupdocs.signature.options/metadatasignoptions/z_order) | Gets or sets the Z-order position of text signature.        <br/>Determines the display order of overlapping signatures. |
| [hash_algorithm](/signature/python-net/groupdocs.signature.options/metadatasignoptions/hash_algorithm) | Gets or sets the hash algorithm to be used for cryptographic operations.<br/>Supported exclusively for digital signatures in PDF files. |
| [signatures](/signature/python-net/groupdocs.signature.options/metadatasignoptions/signatures) | Gets or sets the Metadata of signature. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasignoptions/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encrypt all Metadata signatures withing this options collection.<br/>If this value is set all added signatures will use this encryption by default or its own DataEncryption if it was assigned. |


### Methods
| Method | Description |
| :- | :- |
| [add_pdf_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_pdf_signature/#str-any-str) | Creates new PdfMetadataSignature with passed arguments and adds it to collection. |
| [add_image_signature](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/#int-any) | Creates new ImageMetadataSignature with passed arguments and adds it to collection. |
| [add](/signature/python-net/groupdocs.signature.options/metadatasignoptions/add/#groupdocs.signature.domain.MetadataSignature) | Add existing  MetadataSignature instance to collection. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DocumentType`](/signature/python-net/groupdocs.signature.domain/documenttype)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions)
* class [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
