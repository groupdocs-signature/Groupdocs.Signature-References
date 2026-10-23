---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert einen symmetrischen Verschlüsselungsalgorithmus mit den angegebenen Parametern."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Initialisiert einen symmetrischen Verschlüsselungsalgorithmus mit den angegebenen Parametern.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Symmetrischen Algorithmustyp angeben |
| key | `str` | Verschlüsselungsschlüssel |
| salt | `str` | Passphrase für die Verschlüsselung |

## __init__ {#algorithm_type-key}

Initialisiert einen symmetrischen Verschlüsselungsalgorithmus mit einer Standard-Passphrase.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Symmetrischen Algorithmustyp angeben. |
| key | `str` | Verschlüsselungsschlüssel. |

### Siehe auch
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
