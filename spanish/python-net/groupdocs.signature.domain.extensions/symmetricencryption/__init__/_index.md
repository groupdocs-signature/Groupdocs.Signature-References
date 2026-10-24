---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa un algoritmo de cifrado simétrico con los parámetros especificados."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Inicializa un algoritmo de cifrado simétrico con los parámetros especificados.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Especifique el tipo de algoritmo simétrico |
| key | `str` | Clave de cifrado |
| salt | `str` | Frase de paso para el cifrado |

## __init__ {#algorithm_type-key}

Inicializa un algoritmo de cifrado simétrico con una frase de paso predeterminada.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Especificar tipo de algoritmo simétrico. |
| key | `str` | Clave de cifrado. |

### Ver también
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
