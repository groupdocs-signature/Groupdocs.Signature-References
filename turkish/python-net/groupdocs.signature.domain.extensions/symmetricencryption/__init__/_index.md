---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Belirtilen parametrelerle bir simetrik şifreleme algoritması başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/symmetricencryption/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Belirtilen parametrelerle bir simetrik şifreleme algoritması başlatır.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Simetrik algoritma türünü belirtin |
| key | `str` | Şifreleme anahtarı |
| salt | `str` | Şifreleme için parola |

## __init__ {#algorithm_type-key}

Varsayılan bir parola ile bir simetrik şifreleme algoritması başlatır.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Simetrik algoritma tipini belirtin. |
| key | `str` | Şifreleme anahtarı. |

### Ayrıca Bakınız
* class [`SymmetricEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryption/)
