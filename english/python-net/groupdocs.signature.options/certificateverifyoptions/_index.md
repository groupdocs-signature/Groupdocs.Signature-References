---
title: CertificateVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Keeps options to verify certificate documents."
type: docs
url: /python-net/groupdocs.signature.options/certificateverifyoptions/
is_root: false
weight: 70
---


## CertificateVerifyOptions class

Keeps options to verify certificate documents.

Learn more

- Basic usage of certificate documents by GroupDocs.Signature: Preview Digital Certificates properties (https://docs.groupdocs.com/signature/net/preview-certificate-properties/)

The CertificateVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/) | Initializes a new instance of the TextVerifyOptions with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/__init__/#subject) | Initializes a new CertificateVerifyOptions instance with the subject to verify. |

### Properties
| Property | Description |
| :- | :- |
| [expired](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/expired/) | The property indicates whether the certificate is expired based on the validation result. |
| [issuer](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/issuer/) | The certificate issuer to verify. |
| [match_type](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/match_type/) | The text match type used for verification. |
| [perform_chain_validation](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/perform_chain_validation/) | The verification process should provide X.509 chain validation using the basic validation policy. |
| [serial_number](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/serial_number/) | The certificate serial number to verify. |
| [subject](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/subject/) | The certificate subject to verify. |
| [thumbprint](/signature/python-net/groupdocs.signature.options/certificateverifyoptions/thumbprint/) | The certificate thumbprint to verify. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | The flag indicating whether each document page should be verified. By default the value is True. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | The additional extensions for alternative signature options verification. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | The valid property flag. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | The document page number to be verified; if not set, all pages of the document are verified for the first occurrence (minimum value is 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | The page options to specify pages to be verified. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | The shape position in the document layout used for verifying signatures in headers/footers. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
