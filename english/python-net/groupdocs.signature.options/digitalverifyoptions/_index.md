---
title: DigitalVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 110
---

## DigitalVerifyOptions class

Keeps options to verify document Digital signature.



**Inheritance:** [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions) → 
[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)



The DigitalVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#) | Creates Digital Verification Option with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#System.String) | Creates Digital Verification Option with given digital certificate file path. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#io.RawIOBase) | Creates Digital Verification Option with given certificate stream. |


### Properties
| Property | Description |
| :- | :- |
| [is_valid](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/is_valid) | Valid property flag. |
| [page_number](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/page_number) | Document Page Number to be verified. If property is not set - all Pages of <br/>Document will be verified for first occurrence.<br/>Minimal value is 1. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/pages_setup) | Page Options to specify pages to be verified. |
| [all_pages](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/all_pages) | Flag to verify each document page. By default value is true. |
| [shape_position](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/shape_position) | Specifies shape position in the document layout. For verifing signatures in headers/footers |
| [extensions](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/extensions) | Additional extensions for alternative signature options verification. |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate) | Get X509Certificate2 Certificate from Certificate FilePath or Stream. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password) | Password of Digital Certificate if required. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path) | File path of Digital Certificate. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream) | Stream of Digital Certificate. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments) | Comments of Digital Signature to validate. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from) | Date and time range of Digital Signature to validate. Nullable value will be ignored. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to) | Date and time range of Digital Signature to validate. Nullable value will be ignored. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason) | Reason of Digital Signature to validate. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact) | Signature Contact to validate. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location) | Signature Location to validate. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name) | Subject distinguished name of the certificate to validate. Value is case sensitive.<br/>If this property is set verification will check if Signature subject name contains or equals passed value |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name) | Issuer name of the certificate to validate. Value is case sensitive.<br/>If this property is set verification will check if Signature's issuer name contains or equals passed value |



### Remarks 


**Learn more** |
|
 |
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions)
* class [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)
