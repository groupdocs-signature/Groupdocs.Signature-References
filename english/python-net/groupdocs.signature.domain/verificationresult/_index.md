---
title: VerificationResult class
second_title: GroupDocs.Signature for Python via .NET API References
description: "Represents an instance that keeps results of the verification process."
type: docs
url: /python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 820
---


## VerificationResult class

Represents an instance that keeps results of the verification process.

The VerificationResult type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size/) | The destination document size. For verification this variable always contains zero. |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed/) | The list of signatures that failed the verification process. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid/) | The verification result; True if the verification process was successful, otherwise False. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time/) | The execution time of the process in milliseconds. |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size/) | The source document size in bytes. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded/) | The list of successfully verified signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures/) | The total number of processed signatures. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions
from groupdocs.signature.domain import TextMatchType

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions()
    options.text = "John Smith"
    options.match_type = TextMatchType.CONTAINS

    result = signature.verify(options)

    if result.is_valid:
        print(f"Verified: {len(result.succeeded)} matching signature(s).")
    else:
        print("Verification failed.")
```

### See Also
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
