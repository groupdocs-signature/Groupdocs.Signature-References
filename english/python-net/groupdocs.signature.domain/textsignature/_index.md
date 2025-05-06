---
title: TextSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/textsignature/
is_root: false
weight: 490
---

## TextSignature class

Contains Text signature properties.



**Inheritance:** [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The TextSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textsignature/__init__/#str) | Initialize TextSignature object with signature identifier that was obtained after search process.<br/>This unique identifier is used to find additional properties for this signature from document signature information layer. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/textsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/textsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/textsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/textsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/textsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/textsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/textsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/textsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/textsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/textsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/textsignature/height) | Specifies height of signature. |
| [text](/signature/python-net/groupdocs.signature.domain/textsignature/text) | Specifies text in signature. |
| [signature_implementation](/signature/python-net/groupdocs.signature.domain/textsignature/signature_implementation) | Specifies text signature implementation. |
| [native](/signature/python-net/groupdocs.signature.domain/textsignature/native) | Specifies the native attribute. It is true if signature is document-specific. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textsignature/clone/#) | Clone Text Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`TextSignature`](/signature/python-net/groupdocs.signature.domain/textsignature)
