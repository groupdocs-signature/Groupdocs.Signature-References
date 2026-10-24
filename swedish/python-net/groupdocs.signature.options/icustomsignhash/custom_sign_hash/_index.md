---
title: "custom_sign_hash‑metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Signerar den angivna hash‑värdet med en anpassad signeringsimplementation."
type: docs
url: /sv/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Signerar den angivna hash‑värdet med en anpassad signeringsimplementation.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| signable_hash | `list[int]` | Hash‑värdet som ska signeras. |
| hash_algorithm | `HashAlgorithm` | Hash‑algoritmen som används för att generera hash‑värdet. |
| signature_context | `SignatureContext` | Kontexten som tillhandahåller ytterligare signaturrelaterade alternativ. |

**Returns:** bytes: The signed hash as bytes.

### Se även
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
