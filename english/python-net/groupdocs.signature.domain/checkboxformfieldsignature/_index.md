---
title: CheckboxFormFieldSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/checkboxformfieldsignature/
is_root: false
weight: 80
---

## CheckboxFormFieldSignature class

Contains check-box input form field signature properties.



**Inheritance:** [`CheckboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature) → 
[`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The CheckboxFormFieldSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/__init__/#System.String) | Creates CheckboxFormFieldSignature with predefined name. |
| [__init__](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/__init__/#System.String-bool) | Creates CheckboxFormFieldSignature with predefined name and value |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/height) | Specifies height of signature. |
| [name](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/name) | Specifies unique form field name. |
| [type](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/type) | Specifies Form field type. |
| [value](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/value) | Specifies Form field data object. |
| [checked](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/checked) | Gets or sets checked value of form field check-box input. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature/clone/#) | Clone FormField Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`CheckboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/checkboxformfieldsignature)
* class [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature)
