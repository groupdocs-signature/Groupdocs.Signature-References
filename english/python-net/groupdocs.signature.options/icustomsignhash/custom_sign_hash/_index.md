---
title: custom_sign_hash method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Signs the given hash using a custom signing implementation."
type: docs
url: /python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Signs the given hash using a custom signing implementation.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| signable_hash | `list[int]` | The hash value to be signed. |
| hash_algorithm | `HashAlgorithm` | The hash algorithm used to generate the hash. |
| signature_context | `SignatureContext` | The context providing additional signature-related options. |

**Returns:** bytes: The signed hash as bytes.

### See Also
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
