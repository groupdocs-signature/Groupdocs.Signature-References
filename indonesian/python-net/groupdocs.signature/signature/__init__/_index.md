---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi instance Signature baru dengan dokumen yang disediakan sebagai aliran."
type: docs
url: /id/python-net/groupdocs.signature/signature/__init__/
is_root: false
weight: 10
---


## __init__ {#document}

Menginisialisasi instance Signature baru dengan dokumen yang disediakan sebagai aliran.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran konten dokumen. |

## __init__ {#document-load_options}

Menginisialisasi instance [`Signature`](/signature/python-net/groupdocs.signature/signature/) baru dengan aliran dokumen dan opsi pemuatan.

Pelajari lebih lanjut

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran konten dokumen. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |

## __init__ {#document-settings}

Menginisialisasi instance [`Signature`](/signature/python-net/groupdocs.signature/signature/) baru dengan dokumen yang disediakan melalui aliran dan opsional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

Pelajari lebih lanjut:

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, document, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran konten dokumen. |
| settings | `SignatureSettings` | Pengaturan tanda tangan. |

## __init__ {#document-load_options-settings}

Menginisialisasi instance baru dari [`Signature`](/signature/python-net/groupdocs.signature/signature/) dengan aliran dokumen, opsi pemuatan, dan pengaturan tanda tangan.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, document, load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran konten dokumen. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |
| settings | `SignatureSettings` | Pengaturan tanda tangan. |

## __init__ {#file_path}

Menginisialisasi instance baru dari [`Signature`](/signature/python-net/groupdocs.signature/signature/) dengan dokumen yang disediakan melalui jalur file.

- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

```python
def __init__(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file absolut atau relatif. |

### Contoh

```python
from groupdocs.signature import Signature

# Buka dokumen untuk penandatanganan, pencarian, atau verifikasi
with Signature("sample.pdf") as signature:
    # bekerja dengan objek tanda tangan
    pass
```

## __init__ {#file_path-load_options}

Menginisialisasi instance Signature baru dengan dokumen yang disediakan melalui jalur file dan opsi pemuatan.

- More about file types supported by GroupDocs.Signature: [Document formats supported by GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: [Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: [Load and eSign documents using GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file absolut atau relatif. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |

### Contoh

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # Lakukan operasi penandatanganan, pencarian, atau verifikasi
    pass
```

## __init__ {#file_path-settings}

Menginisialisasi instance [`Signature`](/signature/python-net/groupdocs.signature/signature/) baru dengan dokumen yang disediakan melalui jalur file dan opsional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/).

- More about file types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats
- More about GroupDocs.Signature for .NET features: https://docs.groupdocs.com/display/signaturenet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file absolut atau relatif. |
| settings | `SignatureSettings` | Pengaturan tanda tangan. |

### Contoh

```python
from groupdocs.signature import Signature

# Buka dokumen PDF untuk penandatanganan atau verifikasi
with Signature("sample.pdf") as signature:
    # Gunakan instance tanda tangan di sini (mis., sign, verify, search)
    pass
```

## __init__ {#file_path-load_options-settings}

Menginisialisasi instance baru dari [`Signature`](/signature/python-net/groupdocs.signature/signature/) dengan dokumen yang disediakan melalui jalur file, opsi pemuatan, dan pengaturan tanda tangan.

Pelajari lebih lanjut:
- More about file types supported by GroupDocs.Signature: Document formats supported by GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Supported+Document+Formats)
- More about GroupDocs.Signature for .NET features: Developer Guide (https://docs.groupdocs.com/display/signaturenet/Developer+Guide)
- More about how to open and eSign password-protected documents and document from different storages: Load and eSign documents using GroupDocs.Signature (https://docs.groupdocs.com/display/signaturenet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file absolut atau relatif. |
| load_options | `LoadOptions` | Opsi pemuatan dokumen. |
| settings | `SignatureSettings` | Pengaturan tanda tangan. |

### Contoh

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    # lakukan operasi penandatanganan, verifikasi, atau pencarian
    pass
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
