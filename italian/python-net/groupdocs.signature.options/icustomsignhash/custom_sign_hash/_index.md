---
title: "metodo custom_sign_hash"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Firma l'hash fornito utilizzando un'implementazione di firma personalizzata."
type: docs
url: /it/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Firma l'hash fornito utilizzando un'implementazione di firma personalizzata.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| signable_hash | `list[int]` | Il valore hash da firmare. |
| hash_algorithm | `HashAlgorithm` | L'algoritmo hash utilizzato per generare l'hash. |
| signature_context | `SignatureContext` | Il contesto che fornisce opzioni aggiuntive relative alla firma. |

**Returns:** bytes: The signed hash as bytes.

### Vedi anche
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
