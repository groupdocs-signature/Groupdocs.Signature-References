---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance DigitalVerifyOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance DigitalVerifyOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

Menginisialisasi instance DigitalVerifyOptions dengan jalur file sertifikat digital yang diberikan.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_file_path | `str` | Jalur file ke sertifikat digital. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

Menginisialisasi instance DigitalVerifyOptions dengan aliran sertifikat yang diberikan.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Stream sertifikat. |

### Lihat Juga
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
