---
title: PdfMetadataSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/pdfmetadatasignature/
is_root: false
weight: 320
---

## PdfMetadataSignature class

Contains Pdf Metadata signature properties.



**Inheritance:** [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature) → 
[`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The PdfMetadataSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#System.String) | Creates Pdf Metadata signature with predefined name and empty value |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#System.String-System.Object) | Creates Pdf Metadata signature with predefined values |
| [__init__](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/#System.String-System.Object-System.String) | Creates Pdf Metadata signature with predefined values |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/height) | Specifies height of signature. |
| [name](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/name) | Specifies unique metadata name. |
| [value](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/value) | Specifies metadata object. |
| [type](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/type) | Specifies metadata value type. |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode signature Value properties. |
| [tag_prefix](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/tag_prefix) | The prefix tag of Pdf Metadata signature name. By default this property is set to "xmp".<br/>Possible values are |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/#) | Clone Metadata Signature instance. |
| [clone](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/#System.Object) | Clone Pdf Metadata Signature instance with given value. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_boolean/#) | Converts to boolean. |
| [to_integer](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_integer/#) | Converts to integer. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_decimal/#) | Converts to Decimal. |
| [to_double](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_double/#) | Converts to Double. |
| [to_single](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_single/#) | Converts to float. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_date_time/#) | Converts to DateTime. |
| [to_string](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/to_string/#System.String) | Converts to String with specified format |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature)
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature)
