---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een symmetrisch encryptie-algoritme met de opgegeven parameters."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Initialiseert een symmetrisch encryptie-algoritme met de opgegeven parameters.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Specificeer type symmetrisch algoritme |
| key | `str` | Encryptiesleutel |
| salt | `str` | Wachtwoordzin voor encryptie |

## __init__ {#algorithm_type-key}

Initialiseert een symmetrisch encryptie-algoritme met een standaard wachtwoordzin.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Specificeer symmetrisch algoritme type. |
| key | `str` | Encryptiesleutel. |

### Zie ook
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
