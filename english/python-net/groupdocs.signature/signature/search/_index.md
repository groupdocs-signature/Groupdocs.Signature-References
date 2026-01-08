---
title: search method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signature/search/
is_root: false
weight: 60
---

## search {#System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SearchOptions]]}





```python
def search(self, search_options_list):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| search_options_list | System.Collections.Generic.List`1[[GroupDocs.Signature.Options.SearchOptions]] |  |


## search {#list}

Searches for specified signature types in the document by [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) value.


### Returns 


Returns instance of [`SearchResult`](/signature/python-net/groupdocs.signature.domain/searchresult) with list of found signatures.


```python
def search(self, signature_types):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signature_types | list | One or several types of signatures to find. |



### See Also
* module [`groupdocs.signature`](../../)
* class [`SearchResult`](/signature/python-net/groupdocs.signature.domain/searchresult)
* class [`Signature`](/signature/python-net/groupdocs.signature/signature)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
