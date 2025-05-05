---
title: QrCodeVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/qrcodeverifyoptions/
is_root: false
weight: 350
---

## QrCodeVerifyOptions class

Keeps options to verify document QR-code signature.



**Inheritance:** [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions) → 
[`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions) → 
[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)



The QrCodeVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#) | Creates verification option QrCodeVerifyOptions for QR-Code Signatures. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#str) | Creates verification option QrCodeVerifyOptions for QR-Code Signatures with QR-Code text  to verify. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/#str-groupdocs.signature.domain.QrCodeType) | Creates verification option QrCodeVerifyOptions for QR-Code Signatures with text and QR-Code encode type to verify. |


### Properties
| Property | Description |
| :- | :- |
| [is_valid](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/is_valid) | Valid property flag. |
| [page_number](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/page_number) | Document Page Number to be verified. If property is not set - all Pages of <br/>Document will be verified for first occurrence.<br/>Minimal value is 1. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/pages_setup) | Page Options to specify pages to be verified. |
| [all_pages](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/all_pages) | Flag to verify each document page. By default value is true. |
| [shape_position](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/shape_position) | Specifies shape position in the document layout. For verifing signatures in headers/footers |
| [extensions](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/extensions) | Additional extensions for alternative signature options verification. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/text) | Specify Signature Text if it should be verified. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/match_type) | Gets or sets Text Match Type verification. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/signature_implementation) | Type of Signature to be verified. |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/form_text_field_title) | Gets or sets the title of form field to verify it.<br/>If this property set text will be found only in text form fields. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/form_text_field_type) | Gets or sets the type of form field to verify it.<br/>If this property set text will be found only in text form fields. |
| [signature_id](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/signature_id) | Specify Text Signature ID more than zero if it should be verified. This property is supported only for Pdf documents |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/encode_type) | Gets or sets QR-code Type verification. This property is optional. |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/data_encryption) | Gets or sets implementation of [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption) interface to encode and decode QR-Code Signature Text properties. |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption)
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions)
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions)
* class [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)
