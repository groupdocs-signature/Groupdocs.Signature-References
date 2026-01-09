---
title: TextFormFieldSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 480
---

## TextFormFieldSignature class

Contains text input form field signature properties for Pdf Document



**Inheritance:** [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature) → 
[`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The TextFormFieldSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#System.String) | Creates PdfTextFormFieldSignature with predefined name. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#System.String-System.String) | Creates PdfTextFormFieldSignature with predefined name. |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/height) | Specifies height of signature. |
| [name](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/name) | Specifies unique form field name. |
| [type](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/type) | Specifies Form field type. |
| [value](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/value) | Specifies Form field data object. |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text) | Gets or sets text of form field text input. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/#) | Clone FormField Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature)
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature)
