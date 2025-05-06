---
title: IResult class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/iresult/
is_root: false
weight: 210
---

## IResult class

Common interface for signature process result.



The IResult type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [processing_time](/signature/python-net/groupdocs.signature.domain/iresult/processing_time) | Returns the execution time of the process in milliseconds |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/iresult/total_signatures) | Returns the total processed signatures |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/iresult/source_document_size) | Returns source document size |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/iresult/destin_document_size) | Returns destination document size |
| [succeeded](/signature/python-net/groupdocs.signature.domain/iresult/succeeded) | List of successfully processed signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). |
| [failed](/signature/python-net/groupdocs.signature.domain/iresult/failed) | List of signatures that were not processed [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
