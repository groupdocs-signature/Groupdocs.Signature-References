---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en symmetrisk krypteringsalgoritm med de angivna parametrarna."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Initierar en symmetrisk krypteringsalgoritm med de angivna parametrarna.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Ange typ av symmetrisk algoritm |
| key | `str` | Krypteringsnyckel |
| salt | `str` | Lösenfras för kryptering |

## __init__ {#algorithm_type-key}

Initierar en symmetrisk krypteringsalgoritm med en standardlösenfras.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Ange symmetrisk algoritmtyp. |
| key | `str` | Krypteringsnyckel. |

### Se även
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
