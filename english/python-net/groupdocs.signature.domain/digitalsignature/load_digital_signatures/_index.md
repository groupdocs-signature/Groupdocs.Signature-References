---
title: load_digital_signatures method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/
is_root: false
weight: 30
---

## load_digital_signatures {#}

Load Digital signatures from all system X509 Certificates Stores.


### Returns 


Returns list of [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature) Digital Signatures.


```python
def load_digital_signatures(self):
    ...
```




## load_digital_signatures {#System.String}

Load Digital signatures from a certificate storage.


### Returns 


Returns list of [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature) Digital Signatures.


```python
def load_digital_signatures(self, store_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| store_name | System.String | Custom name of a digital storage containing certificates. |



### See Also
* module [`groupdocs.signature.domain`](../../)
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature)
