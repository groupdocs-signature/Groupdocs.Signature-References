---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi tanda tangan digital dengan parameter default."
type: docs
url: /id/python-net/groupdocs.signature.domain/digitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi tanda tangan digital dengan parameter default.

```python
def __init__(self):
    ...
```

## __init__ {#signature_id}

Menginisialisasi tanda tangan digital dengan pengidentifikasi tanda tangan yang diketahui.

```python
def __init__(self, signature_id):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_id | `str` |  |

## __init__ {#store}

Menginisialisasi DigitalSignature menggunakan sertifikat pertama dari penyimpanan X509 yang ditentukan.

```python
def __init__(self, store):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | penyimpanan X509. |

## __init__ {#store-index}

Menginisialisasi DigitalSignature berdasarkan penyimpanan X509 dan indeks sertifikat yang ditentukan.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | penyimpanan X509. |
| index | `int` | Indeks sertifikat. |

## __init__ {#certificate}

Menginisialisasi tanda tangan digital dengan sertifikat yang ditentukan.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | sertifikat X509. |

### Lihat Juga
* class [`DigitalSignature`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)
