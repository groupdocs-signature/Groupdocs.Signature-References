---
title: BarcodeSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/barcodesignature/
is_root: false
weight: 20
---

## BarcodeSignature class

Contains Barcode Signature properties.



**Inheritance:** [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The BarcodeSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/barcodesignature/__init__/#System.String) | Initialize BarcodeSignature object with signature identifier that was obtained after search process.<br/>This unique identifier is used to find additional properties for this signature from document signature information layer. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/barcodesignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/barcodesignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/barcodesignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/barcodesignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/barcodesignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/barcodesignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/barcodesignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/barcodesignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/barcodesignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/barcodesignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/barcodesignature/height) | Specifies height of signature. |
| [encode_type](/signature/python-net/groupdocs.signature.domain/barcodesignature/encode_type) | Specifies the Barcode Encode Type. |
| [text](/signature/python-net/groupdocs.signature.domain/barcodesignature/text) | Specifies text of Barcode. |
| [format](/signature/python-net/groupdocs.signature.domain/barcodesignature/format) | Specifies the format of Barcode signature image. |
| [content](/signature/python-net/groupdocs.signature.domain/barcodesignature/content) | Specifies Barcode binary data image content of type [`BarcodeSignature.format`](/signature/python-net/groupdocs.signature.domain/barcodesignature#format).<br/>By default this property will not be set.<br/>Use property [`BarcodeSearchOptions.return_content`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions#return_content) to enable this feature. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/barcodesignature/clone/#) | Clone Barcode Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
