---
title: "custom_sign_hash methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Ondertekent de opgegeven hash met behulp van een aangepaste ondertekeningsimplementatie."
type: docs
url: /nl/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Ondertekent de opgegeven hash met behulp van een aangepaste ondertekeningsimplementatie.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signable_hash | `list[int]` | De hashwaarde die ondertekend moet worden. |
| hash_algorithm | `HashAlgorithm` | Het hash-algoritme dat wordt gebruikt om de hash te genereren. |
| signature_context | `SignatureContext` | De context die extra handtekeninggerelateerde opties biedt. |

**Returns:** bytes: The signed hash as bytes.

### Zie ook
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
