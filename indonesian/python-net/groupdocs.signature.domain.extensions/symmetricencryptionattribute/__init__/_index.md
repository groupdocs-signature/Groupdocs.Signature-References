---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi algoritma simetris dengan parameter yang ditentukan."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/__init__/
is_root: false
weight: 10
---


## __init__ {#algorithm_type-key-salt}

Menginisialisasi algoritma simetris dengan parameter yang ditentukan.

```python
def __init__(self, algorithm_type, key, salt):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Tentukan tipe algoritma simetris |
| key | `str` | Kunci enkripsi |
| salt | `str` | Frasa sandi untuk enkripsi |

## __init__ {#algorithm_type-key}

Menginisialisasi algoritma simetris dengan parameter dan frasa sandi default.

```python
def __init__(self, algorithm_type, key):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| algorithm_type | `SymmetricAlgorithmType` | Tipe algoritma enkripsi |
| key | `str` | Kunci enkripsi |

### Lihat Juga
* class [`SymmetricEncryptionAttribute`](/signature/python-net/groupdocs.signature.domain.extensions/symmetricencryptionattribute/)
