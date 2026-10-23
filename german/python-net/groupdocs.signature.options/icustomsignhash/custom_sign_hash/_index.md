---
title: "custom_sign_hash Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Signiert den angegebenen Hash mit einer benutzerdefinierten Signaturimplementierung."
type: docs
url: /de/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Signiert den angegebenen Hash mit einer benutzerdefinierten Signaturimplementierung.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signable_hash | `list[int]` | Der zu signierende Hash-Wert. |
| hash_algorithm | `HashAlgorithm` | Der zum Erzeugen des Hashes verwendete Hash-Algorithmus. |
| signature_context | `SignatureContext` | Der Kontext, der zusätzliche signaturbezogene Optionen bereitstellt. |

**Returns:** bytes: The signed hash as bytes.

### Siehe auch
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
