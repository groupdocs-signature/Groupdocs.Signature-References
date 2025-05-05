---
title: ImageSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/imagesignature/
is_root: false
weight: 260
---

## ImageSignature class

Contains Image signature properties.



**Inheritance:** [`ImageSignature`](/signature/python-net/groupdocs.signature.domain/imagesignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The ImageSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/imagesignature/__init__/#str) | Initialize ImageSignature object with signature identifier that was obtained after search process.<br/>This unique identifier is used to find additional properties for this signature from document signature information layer. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/imagesignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/imagesignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/imagesignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/imagesignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/imagesignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/imagesignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/imagesignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/imagesignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/imagesignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/imagesignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/imagesignature/height) | Specifies height of signature. |
| [size](/signature/python-net/groupdocs.signature.domain/imagesignature/size) | Specifies the size in bytes of signature image. |
| [format](/signature/python-net/groupdocs.signature.domain/imagesignature/format) | Specifies the format of signature image. |
| [content](/signature/python-net/groupdocs.signature.domain/imagesignature/content) | Specifies image binary data content of type [`ImageSignature.format`](/signature/python-net/groupdocs.signature.domain/imagesignature#format).<br/>By default this property will not be set.<br/>Use property [`ImageSearchOptions.return_content`](/signature/python-net/groupdocs.signature.options/imagesearchoptions#return_content) to enable this feature. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/imagesignature/clone/#) | Clone Barcode Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`ImageSignature`](/signature/python-net/groupdocs.signature.domain/imagesignature)
