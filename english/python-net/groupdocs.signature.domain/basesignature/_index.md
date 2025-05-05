---
title: BaseSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/basesignature/
is_root: false
weight: 50
---

## BaseSignature class

Describes base class for signatures.



The BaseSignature type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height) | Specifies height of signature. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/basesignature/clone/#) | Clone signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
