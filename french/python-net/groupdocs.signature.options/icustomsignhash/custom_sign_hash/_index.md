---
title: "méthode custom_sign_hash"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Signe le hachage fourni en utilisant une implémentation de signature personnalisée."
type: docs
url: /fr/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Signe le hachage fourni en utilisant une implémentation de signature personnalisée.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| signable_hash | `list[int]` | La valeur de hachage à signer. |
| hash_algorithm | `HashAlgorithm` | L'algorithme de hachage utilisé pour générer le hachage. |
| signature_context | `SignatureContext` | Le contexte fournissant des options supplémentaires liées à la signature. |

**Returns:** bytes: The signed hash as bytes.

### Voir aussi
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
