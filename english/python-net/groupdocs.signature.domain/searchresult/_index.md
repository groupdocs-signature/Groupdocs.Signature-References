---
title: SearchResult class
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 400
---

## SearchResult class

Result of searching for signatures in specified document.



The SearchResult type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time) | Returns the execution time of the search process in milliseconds. |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures) | Returns the total processed signatures by the search process |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size) | Returns source document size |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size) | Returns destination document size. For Search method it always returns 0. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded) | List of found signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). This list will be always equal to [`SearchResult.signatures`](/signature/python-net/groupdocs.signature.domain/searchresult#signatures) property. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed) | List of signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature) that failed Search process by search criteria.<br/>Supported only for failed Archive documents on Search method. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures) | List of found signatures [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature). |



### See Also
* module [`groupdocs.signature.domain`](..)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`IResult`](/signature/python-net/groupdocs.signature.domain/iresult)
