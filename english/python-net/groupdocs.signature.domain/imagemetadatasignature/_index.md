---
title: ImageMetadataSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/imagemetadatasignature/
is_root: false
weight: 250
---

## ImageMetadataSignature class

Contains Image Metadata signature properties.



**Inheritance:** [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature) → 
[`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The ImageMetadataSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/#int-any) | Creates Image Metadata Signature with Id and value |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/height) | Specifies height of signature. |
| [name](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/name) | Specifies unique metadata name. |
| [value](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/value) | Specifies metadata object. |
| [type](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/type) | Specifies metadata value type. |
| [data_encryption](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode signature Value properties. |
| [id](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/id) | The identifier of Image Metadata signature.<br/>See ImageMetadataSignatures class that contains standard Signature with predefined Id value. |
| [size](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/size) | Read-only value to get size of Metadata value |
| [description](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/description) | Read-only value to get description for standard Image Metadata signature |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#) | Clone Metadata Signature instance. |
| [clone](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/clone/#any) | Clone Image Metadata Signature instance with given value. |
| [to_boolean](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_boolean/#) | Converts to boolean. |
| [to_integer](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_integer/#) | Converts to integer. |
| [to_decimal](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/#) | Converts to Decimal. |
| [to_double](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/#) | Converts to Double. |
| [to_single](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/#) | Converts to float. |
| [to_date_time](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/#) | Converts to DateTime. |
| [to_string](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/#str) | Converts to String with specified format |
| [to_long](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/to_long/#) | Converts to long. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature)
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature)
