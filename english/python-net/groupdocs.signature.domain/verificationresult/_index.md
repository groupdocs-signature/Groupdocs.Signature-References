---
title: VerificationResult class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/verificationresult/
is_root: false
weight: 520
---

## VerificationResult class

Instance to keep results of verification process.



The VerificationResult type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [processing_time](/signature/python-net/groupdocs.signature.domain/verificationresult/processing_time) | Returns the execution time of the process in milliseconds. |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/verificationresult/total_signatures) | Returns the total processed signatures |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/source_document_size) | Returns source document size in bytes |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/verificationresult/destin_document_size) | Returns the destination document size. For verification this variable always contains zero. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/verificationresult/succeeded) | List of successfully verified signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). |
| [failed](/signature/python-net/groupdocs.signature.domain/verificationresult/failed) | List of signatures that failed verification process.<br/>Currently this property is not supported. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/verificationresult/is_valid) | Returns true if Verification process was successful otherwise false. |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`IResult`](/signature/python-net/groupdocs.signature.domain/iresult)
