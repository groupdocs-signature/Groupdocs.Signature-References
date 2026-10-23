---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas DigitalSignOptions dengan nilai default.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

Menginisialisasi instance baru DigitalSignOptions dengan file sertifikat.

```python
def __init__(self, certificate_file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_file_path | `str` | Jalur file sertifikat digital. |

### Contoh

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

Menginisialisasi instance baru DigitalSignOptions dengan aliran sertifikat.

```python
def __init__(self, certificate_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Aliran Sertifikat Digital. |

### Contoh

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

Menginisialisasi instance baru dari kelas DigitalSignOptions dengan file sertifikat dan file gambar tampilan.

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_file_path | `str` | Jalur file sertifikat digital. |
| image_file_path | `str` | Jalur file gambar tampilan tanda tangan. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Berikan sertifikat dan gambar tampilan ke konstruktor
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

Menginisialisasi instance baru DigitalSignOptions dengan file sertifikat dan aliran gambar tampilan.

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_file_path | `str` | Jalur file sertifikat digital. |
| appearence_image_stream | `io.RawIOBase` | Aliran gambar tampilan tanda tangan. |

### Contoh

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

Menginisialisasi instance baru DigitalSignOptions dengan aliran sertifikat dan file gambar tampilan.

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase. Aliran Sertifikat Digital. |
| image_file_path | `str` | str. Jalur file gambar Tampilan Tanda Tangan. |

## __init__ {#certificate_stream-appearence_image_stream}

Menginisialisasi instance baru DigitalSignOptions dengan aliran sertifikat dan aliran gambar tampilan.

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | Aliran Sertifikat Digital. |
| appearence_image_stream | `io.RawIOBase` | Aliran gambar tampilan tanda tangan. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # Muat sertifikat dan gambar tampilan dari aliran
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### Lihat Juga
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
