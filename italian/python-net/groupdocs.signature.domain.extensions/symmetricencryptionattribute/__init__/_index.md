---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza un algoritmo simmetrico con i parametri specificati."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Inizializza un algoritmo simmetrico con i parametri specificati.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Specifica il tipo di algoritmo simmetrico |
| key | `str` | Chiave di crittografia |
| salt | `str` | Frase segreta per la crittografia |

## __init__ {#algorithm_type-key}

Inizializza un algoritmo simmetrico con parametri e una passphrase predefinita.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Tipo di algoritmo di crittografia |
| key | `str` | Chiave di crittografia |

### Vedi anche
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
