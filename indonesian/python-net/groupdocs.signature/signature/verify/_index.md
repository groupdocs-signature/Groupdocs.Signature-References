---
title: "metode verify"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan."
type: docs
url: /id/python-net/groupdocs.signature/signature/verify/
is_root: false
weight: 1270
---


## verify {#verify_options}

Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan.

Lebih banyak tentang verifikasi dokumen yang ditandatangani secara elektronik menggunakan GroupDocs.Signature:
- [How to verify document is electronically signed in C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures)

```python
def verify(self, verify_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Opsi verifikasi tanda tangan. |

**Returns:** VerificationResult: Result of the verification. The `is_valid` property is True if verification succeeded.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options-predicate}

Memverifikasi tanda tangan dokumen menggunakan opsi verifikasi yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan.

Pelajari lebih lanjut

- More about electronically signed documents verification using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures

```python
def verify(self, verify_options, predicate):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| verify_options | `VerifyOptions` | Opsi verifikasi tanda tangan. |
| predicate | `Func[BaseSignature, bool]` | Predikat filter untuk menentukan tanda tangan mana yang harus diverifikasi. |

**Returns:** list[BaseSignature]: Instances that satisfy the provided predicate.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options, lambda s: True)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list}

Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions.

Lebih banyak tentang verifikasi dokumen yang ditandatangani secara elektronik menggunakan GroupDocs.Signature: [Cara memverifikasi dokumen ditandatangani secara elektronik dalam C#](https://docs.groupdocs.com/display/signaturenet/Verify+document+for+signatures).

```python
def verify(self, verify_options_list):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Koleksi opsi verifikasi tanda tangan. Instance dari `GroupDocs.Signature.Options.VerifyOptionsCollection`. |

**Returns:** VerificationResult: The verification result. The `IsValid` property is True if the verification process was successful.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## verify {#verify_options_list-predicate}

Memverifikasi tanda tangan dokumen menggunakan opsi verifikasi yang disediakan dan menyaring hasil dengan predikat yang diberikan.

Metode ini pertama mencari tanda tangan yang cocok dengan opsi verifikasi, menyaringnya menggunakan predikat, dan kemudian memverifikasi hanya tanda tangan yang telah disaring tersebut.

- Learn more: More about electronically signed documents verification using GroupDocs.Signature: How to verify document is electronically signed in C#.

```python
def verify(self, verify_options_list, predicate):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| verify_options_list | `List[VerifyOptions]` | Koleksi opsi verifikasi tanda tangan. |
| predicate | `Func[BaseSignature, bool]` | Predikat filter untuk menentukan tanda tangan mana yang harus diverifikasi. |

**Returns:** list[BaseSignature]: List of signatures that satisfy the provided predicate.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify([options], lambda s: s.text == "John Smith")
        print(f"Document is signed by John Smith: {result[0].is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
