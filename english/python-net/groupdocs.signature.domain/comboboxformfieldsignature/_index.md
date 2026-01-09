---
title: ComboboxFormFieldSignature class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/comboboxformfieldsignature/
is_root: false
weight: 90
---

## ComboboxFormFieldSignature class

Contains combo-box input form field signature properties.



**Inheritance:** [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature) → 
[`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature) → 
[`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)



The ComboboxFormFieldSignature type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/__init__/#System.String) | Creates ComboboxFormFieldSignature with predefined name. |
| [__init__](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/__init__/#System.String-System.Collections.Generic.List`1[[System.String]]) | Constructs a new instance of ComboboxFormFieldSignature |
| [__init__](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/__init__/#System.String-System.Collections.Generic.List`1[[System.String]]-System.Object) | Constructs a new instance of ComboboxFormFieldSignature |


### Properties
| Property | Description |
| :- | :- |
| [signature_type](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/signature_type) | Specifies the type of signature. |
| [page_number](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/page_number) | Specifies the page signature was found on. |
| [signature_id](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/signature_id) | Unique signature identifier to modify signature in the document over Update or Delete methods.<br/>This property will be set automatically after Sign or Search method being called.<br/>If this property was saved before it can be set manually to manipulate the signature. |
| [is_signature](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/is_signature) | Get or set flag to indicate if this component is Signature or document content.<br/>This property is being used with Update method to set element as signature (true) or document element (false). |
| [deleted](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/deleted) | Get the flag that indicates if this signature was deleted from the document.<br/>This property is being used only for document history log records to keep the list of deleted signatures. |
| [created_on](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/created_on) | Get or set the signature creation date. |
| [modified_on](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/modified_on) | Get or set the signature modification date. |
| [top](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/top) | Specifies top position of signature. |
| [left](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/left) | Specifies left position of signature. |
| [width](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/width) | Specifies width of signature. |
| [height](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/height) | Specifies height of signature. |
| [name](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/name) | Specifies unique form field name. |
| [type](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/type) | Specifies Form field type. |
| [value](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/value) | Specifies Form field data object. |
| [selected](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/selected) | Get or set selected value. |
| [items](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/items) | Get or set combo-box options list. |


### Methods
| Method | Description |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/#) | Clone FormField Signature instance. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature)
* class [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature)
