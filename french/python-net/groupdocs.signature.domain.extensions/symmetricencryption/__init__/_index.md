---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise un algorithme de chiffrement symétrique avec les paramètres spécifiés."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Initialise un algorithme de chiffrement symétrique avec les paramètres spécifiés.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Spécifier le type d'algorithme symétrique |
| key | `str` | Clé de chiffrement |
| salt | `str` | Phrase de passe pour le chiffrement |

## __init__ {#algorithm_type-key}

Initialise un algorithme de chiffrement symétrique avec une phrase de passe par défaut.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Spécifiez le type d'algorithme symétrique. |
| key | `str` | Clé de chiffrement. |

### Voir aussi
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
