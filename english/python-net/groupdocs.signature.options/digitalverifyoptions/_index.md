---
title: DigitalVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Keeps options to verify a document's digital signature."
type: docs
url: /python-net/groupdocs.signature.options/digitalverifyoptions/
is_root: false
weight: 150
---


## DigitalVerifyOptions class

Keeps options to verify a document's digital signature.

Learn more

- Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
- Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings

The DigitalVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/) | Initializes a DigitalVerifyOptions instance with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_file_path) | Initializes a DigitalVerifyOptions instance with the given digital certificate file path. |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/#certificate_stream) | Initializes a DigitalVerifyOptions instance with the given certificate stream. |

### Properties
| Property | Description |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate/) | The X509Certificate2 certificate obtained from the certificate file path or stream. |
| [certificate_file_path](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_file_path/) | The file path of the digital certificate. |
| [certificate_stream](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/certificate_stream/) | The stream of the digital certificate. |
| [comments](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/comments/) | The comments of the digital signature to validate. |
| [contact](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/contact/) | The signature contact to validate. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/issuer_name/) | The issuer name of the certificate to validate. |
| [location](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/location/) | The signature location to validate. |
| [password](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/password/) | The password of the digital certificate if required. |
| [reason](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/reason/) | The reason of the digital signature to validate. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_from/) | The start of the date and time range of the digital signature to validate. A None value will be ignored. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/sign_date_time_to/) | The end of the date and time range of the digital signature to validate. A null value will be ignored. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/subject_name/) | The subject distinguished name of the certificate to validate; verification checks if the signature's subject name contains or equals this case‑sensitive value. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | The flag indicating whether each document page should be verified. By default the value is True. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | The additional extensions for alternative signature options verification. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | The valid property flag. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | The document page number to be verified; if not set, all pages of the document are verified for the first occurrence (minimum value is 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | The page options to specify pages to be verified. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | The shape position in the document layout used for verifying signatures in headers/footers. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
