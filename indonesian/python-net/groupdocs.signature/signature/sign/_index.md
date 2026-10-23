---
title: "metode sign"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menandai dokumen dengan SignOptions dan menyimpan hasil ke aliran."
type: docs
url: /id/python-net/groupdocs.signature/signature/sign/
is_root: false
weight: 1190
---


## sign {#document-sign_options}

Menandatangani dokumen dengan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran.

```python
def sign(self, document, sign_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran dokumen keluaran. |
| sign_options | `SignOptions` | Opsi tanda tangan. |

**Returns:** SignResult: Instance containing list of newly created signatures.

Catatan:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#document-sign_options-save_options}

Menandatangani dokumen dengan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya.

Pelajari lebih lanjut
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, document, sign_options, save_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran dokumen keluaran. |
| sign_options | `SignOptions` | Opsi tanda tangan. |
| save_options | `SaveOptions` | Opsi penyimpanan. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list}

Menandatangani dokumen dengan kumpulan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran.

Pelajari lebih lanjut

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, document, sign_options_list):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran dokumen keluaran. |
| sign_options_list | `List[SignOptions]` | Daftar opsi tanda tangan. |

**Returns:** SignResult: Instance with list of newly created signatures.

## sign {#document-sign_options_list-save_options}

Menandatangani dokumen dengan kumpulan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya.

```python
def sign(self, document, sign_options_list, save_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| document | `io.RawIOBase` | Aliran dokumen keluaran. |
| sign_options_list | `List[SignOptions]` | Daftar opsi tanda tangan. |
| save_options | `SaveOptions` | Opsi penyimpanan. |

**Returns:** SignResult: Instance containing the list of newly created signatures.

Catatan:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how to save electronically signed documents and customize the saving process: https://docs.groupdocs.com/display/signaturenet/Saving

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Tandatangani dan simpan hasil ke file baru; sumber tetap tidak berubah
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options}

Menandatangani dokumen dengan SignOptions dan menyimpan hasil ke jalur file yang ditentukan.

Pelajari lebih lanjut

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur berkas keluaran. |
| sign_options | `SignOptions` | Opsi tanda tangan. |

**Returns:** SignResult: Instance of SignResult with list of newly created signatures.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options-save_options}

Menandatangani dokumen dengan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke jalur file yang ditentukan menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya.

- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options, save_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur berkas keluaran. |
| sign_options | `SignOptions` | Opsi tanda tangan. |
| save_options | `SaveOptions` | Opsi penyimpanan. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Buka dokumen; blok with melepaskan file saat selesai
    with Signature("sample.pdf") as signature:
        # Tanda tangan teks 100 piksel dari tepi kiri dan atas halaman pertama
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Tandatangani dan simpan hasil ke file baru; sumber tetap tidak berubah
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list}

Menandatangani dokumen dengan koleksi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke jalur file yang ditentukan.

Pelajari lebih lanjut:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing

```python
def sign(self, file_path, sign_options_list):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur berkas keluaran. |
| sign_options_list | `List[SignOptions]` | Daftar opsi tanda tangan. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    options.left = 100
    options.top = 100
    result = signature.sign("signed_sample.pdf", options)
    print(f"Signatures added: {len(result.succeeded)}")
```

## sign {#file_path-sign_options_list-save_options}

Menandatangani dokumen dengan kumpulan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke jalur file yang ditentukan menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya.

Pelajari lebih lanjut:
- More about electronic signature types supported by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Electronic+signature+types
- More about how eSign documents in C#: https://docs.groupdocs.com/display/signaturenet/Signing
- More about how save electronically signed documents and customize saving process: https://docs.groupdocs.com/display/signaturenet/Saving

```python
def sign(self, file_path, sign_options_list, save_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur berkas keluaran. |
| sign_options_list | `List[SignOptions]` | Daftar opsi tanda tangan. |
| save_options | `SaveOptions` | Opsi penyimpanan. |

**Returns:** SignResult: Instance with list of newly created signatures.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

with Signature("sample.pdf") as signature:
    options = TextSignOptions("John Smith")
    result = signature.sign("signed_sample.pdf", [options])
    print(f"Signatures added: {len(result.succeeded)}")
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
