---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует симметричный алгоритм с указанными параметрами."
type: docs
url: /ru/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Инициализирует симметричный алгоритм с указанными параметрами.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Укажите тип симметричного алгоритма |
| key | `str` | Ключ шифрования |
| salt | `str` | Пароль для шифрования |

## __init__ {#algorithm_type-key}

Инициализирует симметричный алгоритм с параметрами и паролем по умолчанию.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Тип алгоритма шифрования |
| key | `str` | Ключ шифрования |

### См. также
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
