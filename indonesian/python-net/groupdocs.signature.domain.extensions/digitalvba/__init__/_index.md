---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas DigitalVBA dengan file sertifikat."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

Menginisialisasi instance baru dari kelas DigitalVBA dengan file sertifikat.

```python
def __init__(self, certificate_file_path, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_file_path | `str` | Jalur file sertifikat digital. |
| password | `str` | Kata sandi sertifikat digital. |

### Contoh

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# Buat ekstensi DigitalVBA menggunakan file sertifikat dan kata sandi
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

Menginisialisasi instance baru dari kelas DigitalVBA dengan aliran sertifikat.

```python
def __init__(self, certificate_stream, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase yang berisi sertifikat digital. |
| password | `str` | str kata sandi untuk sertifikat digital. |

### Lihat Juga
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
