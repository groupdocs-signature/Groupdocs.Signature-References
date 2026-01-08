---
title: BarcodeVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/barcodeverifyoptions/
is_root: false
weight: 30
---

## BarcodeVerifyOptions class

Represents the Barcode verify options.



**Inheritance:** [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions) → 
[`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions) → 
[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)



The BarcodeVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#) | Creates default Verification Option for Barcode Signature. |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#System.String) | Creates default Verification Option with verification text |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#groupdocs.signature.domain.BarcodeType) | Creates default Verification Option with Barcode Type verification |
| [__init__](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/#System.String-groupdocs.signature.domain.BarcodeType) | Creates default Verification Option with Barcode Type verification and text |


### Properties
| Property | Description |
| :- | :- |
| [is_valid](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/is_valid) | Valid property flag. |
| [page_number](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/page_number) | Document Page Number to be verified. If property is not set - all Pages of <br/>Document will be verified for first occurrence.<br/>Minimal value is 1. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/pages_setup) | Page Options to specify pages to be verified. |
| [all_pages](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/all_pages) | Flag to verify each document page. By default value is true. |
| [shape_position](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/shape_position) | Specifies shape position in the document layout. For verifing signatures in headers/footers |
| [extensions](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/extensions) | Additional extensions for alternative signature options verification. |
| [text](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/text) | Specify Signature Text if it should be verified. |
| [match_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/match_type) | Gets or sets Text Match Type verification. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/signature_implementation) | Type of Signature to be verified. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/form_text_field_title) | Gets or sets the title of form field to verify it.<br/>If this property set text will be found only in text form fields. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/form_text_field_type) | Gets or sets the type of form field to verify it.<br/>If this property set text will be found only in text form fields. |
| [signature_id](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/signature_id) | Specify Text Signature ID more than zero if it should be verified. This property is supported only for Pdf documents |
| [encode_type](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/encode_type) | Gets or sets Barcode Type verification. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions)
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions)
* class [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)
