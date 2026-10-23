---
title: "metode search"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mencari tanda tangan dalam dokumen menggunakan daftar SearchOptions."
type: docs
url: /id/python-net/groupdocs.signature/signature/search/
is_root: false
weight: 1140
---


## search {#search_options_list}

Mencari tanda tangan dalam dokumen menggunakan daftar [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/).

Pelajari lebih lanjut

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Koleksi opsi pencarian. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([TextSearchOptions()])
    for found in result.signatures:
        print(f"Text signature '{found.text}' on page {found.page_number}")
```

## search {#search_options_list-predicate}

Mencari tanda tangan dalam dokumen menggunakan opsi pencarian yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan.

Pelajari lebih lanjut:
- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, search_options_list, predicate):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_options_list | `List[SearchOptions]` | Daftar instance `SearchOptions` yang mendefinisikan kriteria untuk mencari tanda tangan. |
| predicate | `Func[BaseSignature, bool]` | Predicate filter yang diterapkan pada daftar tanda tangan yang ditemukan. |

**Returns:** SearchResult: A `SearchResult` containing the signatures that match the specified search options and satisfy the predicate.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Cari tanda tangan teks pada setiap halaman
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#search_options}

```python
def search(self, search_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| search_options | `SearchOptions` |  |

## search {#signature_type}

```python
def search(self, signature_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_type | `SignatureType` |  |

## search {#signature_types}

Mencari tipe tanda tangan yang ditentukan dalam dokumen berdasarkan nilai `SignatureType`.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, signature_types):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_types | `list[SignatureType]` | Satu atau beberapa jenis tanda tangan untuk ditemukan. |

**Returns:** SearchResult: Instance containing the list of found signatures.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Cari tanda tangan teks pada setiap halaman
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```

## search {#predicate}

Mencari tanda tangan dalam dokumen menggunakan semua opsi pencarian yang tersedia dan menyaring hasil berdasarkan predikat yang ditentukan.

- More about search electronic signatures in a documents using GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+electronic+signatures+in+document
- More about electronic signatures search dependent on eSign type: https://docs.groupdocs.com/display/signaturenet/Searching

```python
def search(self, predicate):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| predicate | `Func[BaseSignature, bool]` | Callable[[BaseSignature], bool] – sebuah fungsi yang menerima `BaseSignature` dan mengembalikan `True` untuk mempertahankan tanda tangan atau `False` untuk membuangnya. |

**Returns:** list[BaseSignature]: A list of `BaseSignature` instances that satisfy the provided predicate.

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def is_text_signature(sig):
    return hasattr(sig, "text") and sig.text.startswith("Invoice")

with Signature("signed.pdf") as signature:
    # Cari tanda tangan teks dan filter mereka dengan predicate khusus
    result = signature.search([TextSearchOptions()], predicate=is_text_signature)
    for found in result.signatures:
        print(f"Found text signature: {found.text} on page {found.page_number}")
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
