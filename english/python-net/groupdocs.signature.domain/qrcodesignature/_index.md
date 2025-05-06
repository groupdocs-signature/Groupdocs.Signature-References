---
title: QrCodeSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 360
---

## QrCodeSignature class

Contains QR-code signature properties.



**Inheritance:** [`QrCodeSignature`](/signature/python-net/groupdocs.signature.domain/qrcodesignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The QrCodeSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#str) | Initialize QrCodeSignature object with signature identifier that was obtained after search process.<br/>This unique identifier is used to find additional properties for this signature from document signature information layer. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/qrcodesignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/qrcodesignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/qrcodesignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/qrcodesignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/qrcodesignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/qrcodesignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/qrcodesignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/qrcodesignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/qrcodesignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/qrcodesignature/height) | Specifies height of signature. |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type) | Specifies the QR-code Encode Type. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text) | Specifies text of QR-code. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format) | Specifies the format of QR-code signature image. |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content) | Specifies QR-code binary data image content of type [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature#format).<br/>By default this property will not be set.<br/>Use property [`QrCodeSearchOptions.return_content`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions#return_content) to enable this feature. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/#) | Clone QR-Code Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`QrCodeSignature`](/signature/python-net/groupdocs.signature.domain/qrcodesignature)
