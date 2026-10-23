---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi tanda tangan digital PDF tanpa sertifikat."
type: docs
url: /id/python-net/groupdocs.signature.domain/pdfdigitalsignature/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi tanda tangan digital PDF tanpa sertifikat.

```python
def __init__(self):
    ...
```

## __init__ {#store}

Menginisialisasi tanda tangan digital PDF menggunakan penyimpanan X509 yang ditentukan. Sertifikat pertama dari penyimpanan akan digunakan.

```python
def __init__(self, store):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | penyimpanan X509. |

## __init__ {#store-index}

Menginisialisasi tanda tangan digital PDF menggunakan penyimpanan X509 yang ditentukan dan indeks sertifikat.

```python
def __init__(self, store, index):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| store | `System.Security.Cryptography.X509Certificates.X509Store` | penyimpanan X509. |
| index | `int` | Indeks sertifikat. |

## __init__ {#certificate}

Menginisialisasi tanda tangan digital PDF dengan sertifikat X509 yang ditentukan.

```python
def __init__(self, certificate):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate | `System.Security.Cryptography.X509Certificates.X509Certificate2` | sertifikat X509. |

### Lihat Juga
* class [`PdfDigitalSignature`](/signature/python-net/groupdocs.signature.domain/pdfdigitalsignature/)
