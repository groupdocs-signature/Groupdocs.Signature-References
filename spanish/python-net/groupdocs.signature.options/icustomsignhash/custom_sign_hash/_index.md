---
title: "método custom_sign_hash"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Firma el hash proporcionado utilizando una implementación de firma personalizada."
type: docs
url: /es/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Firma el hash proporcionado utilizando una implementación de firma personalizada.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signable_hash | `list[int]` | El valor hash a firmar. |
| hash_algorithm | `HashAlgorithm` | El algoritmo hash utilizado para generar el hash. |
| signature_context | `SignatureContext` | El contexto que proporciona opciones adicionales relacionadas con la firma. |

**Returns:** bytes: The signed hash as bytes.

### Ver también
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
