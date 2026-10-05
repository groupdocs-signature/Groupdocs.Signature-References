---
title: TextVerifyOptions class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Keeps options to verify document Text signature."
type: docs
url: /python-net/groupdocs.signature.options/textverifyoptions/
is_root: false
weight: 600
---


## TextVerifyOptions class

Keeps options to verify document Text signature.

Learn more:
- Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures+in+the+document)
- Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](https://docs.groupdocs.com/display/signaturenet/Verify+Text+signatures)

The TextVerifyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/) | Initializes a new instance of the TextVerifyOptions with default values. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text) | Initializes a new instance of the TextVerifyOptions with verification text. |
| [__init__](/signature/python-net/groupdocs.signature.options/textverifyoptions/__init__/#text-implementation) | Initializes a new TextVerifyOptions instance with the text to verify and the signature implementation type. |

### Properties
| Property | Description |
| :- | :- |
| [form_text_field_title](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_title/) | The title of the form field to verify. If set, the text will be found only in text form fields. |
| [form_text_field_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/form_text_field_type/) | The type of form field to verify; if set, text will be found only in text form fields. |
| [match_type](/signature/python-net/groupdocs.signature.options/textverifyoptions/match_type/) | The text match type verification. |
| [signature_id](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_id/) | The Text Signature ID to verify. Must be greater than zero; supported only for PDF documents. |
| [signature_implementation](/signature/python-net/groupdocs.signature.options/textverifyoptions/signature_implementation/) | The type of signature to be verified. |
| [text](/signature/python-net/groupdocs.signature.options/textverifyoptions/text/) | The signature text to verify. |
| [all_pages](/signature/python-net/groupdocs.signature.options/verifyoptions/all_pages/) | The flag indicating whether each document page should be verified. By default the value is True. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [extensions](/signature/python-net/groupdocs.signature.options/verifyoptions/extensions/) | The additional extensions for alternative signature options verification. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [is_valid](/signature/python-net/groupdocs.signature.options/verifyoptions/is_valid/) | The valid property flag. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/verifyoptions/page_number/) | The document page number to be verified; if not set, all pages of the document are verified for the first occurrence (minimum value is 1). (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/verifyoptions/pages_setup/) | The page options to specify pages to be verified. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/verifyoptions/shape_position/) | The shape position in the document layout used for verifying signatures in headers/footers. (inherited from [`VerifyOptions`](/signature/python-net/groupdocs.signature.options/verifyoptions/)) |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### See Also
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
