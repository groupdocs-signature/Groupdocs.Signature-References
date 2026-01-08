---
title: custom_sign_hash method
second_title: GroupDocs.Signature for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 20
---

## custom_sign_hash {#bytes-groupdocs.signature.domain.HashAlgorithm-groupdocs.signature.options.SignatureContext}

Signs the given hash using a custom signing implementation.


### Returns 


The signed hash as a byte array.


```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| signable_hash | bytes | The hash value to be signed. |
| hash_algorithm | groupdocs.signature.domain.HashAlgorithm | The hash algorithm used to generate the hash. |
| signature_context | groupdocs.signature.options.SignatureContext | The context providing additional signature-related options. |



### See Also
* module [`groupdocs.signature.options`](../../)
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash)
