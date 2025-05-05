---
title: delete method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 20
---

## delete {#groupdocs.signature.domain.BaseSignature}

Deletes passed signature [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature) from the document.


### Returns 


Returns true if operation was successful.


```python
def delete(self, signature):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signature | groupdocs.signature.domain.BaseSignature | Signature object to be removed from the document. |


## delete {#System.Collections.Generic.List<GroupDocs.Signature.Domain.BaseSignature>}





```python
def delete(self, signatures):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signatures | System.Collections.Generic.List<GroupDocs.Signature.Domain.BaseSignature> |  |


## delete {#groupdocs.signature.domain.SignatureType}

Deletes signatures of the certain type [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype) from the document.
Only signatures that were added by Sign method and marked as Signatures [`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature#is_signature)  will be removed.
Following signature types are supported: Text, Image, Digital, Barcode, QR-Code


### Returns 


Returns DeleteResult [`DeleteResult`](/signature/python-net/groupdocs.signature.domain/deleteresult) with list of successfully deleted signatures and failed ones.


```python
def delete(self, signature_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signature_type | groupdocs.signature.domain.SignatureType | The type of signatures to be removed from the document. |


## delete {#System.Collections.Generic.List<GroupDocs.Signature.Domain.SignatureType>}





```python
def delete(self, signature_types):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signature_types | System.Collections.Generic.List<GroupDocs.Signature.Domain.SignatureType> |  |


## delete {#str}

Deletes signature by its specific signature Id from the document.


### Returns 


Returns true if operation was successful.


```python
def delete(self, signature_id):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signature_id | str | The Id of the signature to be removed from the document. |


## delete {#System.Collections.Generic.List<string>}





```python
def delete(self, signature_ids):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signature_ids | System.Collections.Generic.List<string> |  |



### See Also
* module [`groupdocs.signature`](../../)
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature)
* class [`DeleteResult`](/signature/python-net/groupdocs.signature.domain/deleteresult)
* class [`Signature`](/signature/python-net/groupdocs.signature/signature)
* class [`SignatureType`](/signature/python-net/groupdocs.signature.domain/signaturetype)
