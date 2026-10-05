---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a symmetric algorithm with the specified parameters."
type: docs
url: /python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Initializes a symmetric algorithm with the specified parameters.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Specify symmetric algorithm type |
| key | `str` | Encryption key |
| salt | `str` | Passphrase for encryption |

## __init__ {#algorithm_type-key}

Initializes a symmetric algorithm with parameters and a default passphrase.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Encryption algorithm type |
| key | `str` | Encryption key |

### See Also
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
