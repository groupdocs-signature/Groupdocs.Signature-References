---
title: CertificateVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 60
---

## CertificateVerifyOptions class

Keeps options to verify certificate documents.



**Inheritance:** [`CertificateVerifyOptions`](/signature/python-net/groupdocs.signature.options/certificateverifyoptions) → 
[`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)



The CertificateVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#) | Initializes a new instance of the TextVerifyOptions with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#System.String) | Initializes a new instance of the CertificateVerifyOptions with subject to verify. |


### Properties
| Property | Description |
| :- | :- |
| [is_valid](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/is_valid) | Valid property flag. |
| [page_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/page_number) | Document Page Number to be verified. If property is not set - all Pages of <br/>Document will be verified for first occurrence.<br/>Minimal value is 1. |
| [pages_setup](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/pages_setup) | Page Options to specify pages to be verified. |
| [all_pages](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/all_pages) | Flag to verify each document page. By default value is true. |
| [shape_position](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/shape_position) | Specifies shape position in the document layout. For verifing signatures in headers/footers |
| [extensions](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/extensions) | Additional extensions for alternative signature options verification. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer) | Specify Certificate Issuer if it should be verified. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number) | Specify Certificate Serial Number if it should be verified. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject) | Specify Certificate subject if it should be verified. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint) | Specify Certificate Thumbprint if it should be verified. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type) | Gets or sets Text Match Type verification. |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired) | Indicates if certificate is expired date due validation result.<br/>Property is read-only. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation) | Get or set if verification process should provide X.509 chain validation using basic validation policy.<br/>By default this value is true. |



### Remarks 


**Learn more** |
|
 |

### See Also
* module [`groupdocs.signature.options`](..)
* class [`CertificateVerifyOptions`](/signature/python-net/groupdocs.signature.options/certificateverifyoptions)
* class [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions)
