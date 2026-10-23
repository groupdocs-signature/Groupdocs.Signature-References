---
title: "metode delete"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menghapus BaseSignature yang ditentukan dari dokumen."
type: docs
url: /id/python-net/groupdocs.signature/signature/delete/
is_root: false
weight: 1010
---


## delete {#signature}

Menghapus [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) yang ditentukan dari dokumen.

Pelajari lebih lanjut:
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature | `BaseSignature` | Objek BaseSignature yang akan dihapus dari dokumen. |

**Returns:** bool: True if the operation was successful, otherwise False.

### Contoh

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_first_text_signature():
    # delete() menyimpan perubahan ke dokumen yang dibuka, jadi kerjakan pada salinan.
    shutil.copy("signed.docx", "text_signature_deleted.docx")
    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return
        if signature.delete(signatures[0]):
            print("Signature deleted")
```

## delete {#signatures}

Menghapus daftar tanda tangan yang disediakan dari dokumen.

- More about how to delete electronic signature from document in C#: [How to delete eSignature from document with GroupDocs.Signature](https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents)
- Advanced use cases of deleting document eSignatures: [How to delete different types of eSignatures from document in C#](https://docs.groupdocs.com/display/signaturenet/Deleting)

```python
def delete(self, signatures):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signatures | `List[BaseSignature]` | Daftar tanda tangan yang akan dihapus dari dokumen. |

**Returns:** DeleteResult: Result containing lists of successfully deleted signatures and those that failed.

### Contoh

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Kerjakan pada salinan karena delete() menyimpan perubahan ke dokumen yang dibuka.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        print(f"Found {len(signatures)} text signature(s)")
        if not signatures:
            return

        # Hapus tanda tangan pertama yang ditemukan.
        if signature.delete([signatures[0]]):
            print("Signature deleted successfully")
        else:
            print("Signature could not be deleted")
```

## delete {#signature_type}

Menghapus tanda tangan dengan tipe yang ditentukan dari dokumen.

Hanya tanda tangan yang ditambahkan oleh metode `Sign` dan ditandai sebagai tanda tangan ([`BaseSignature.IsSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) yang akan dihapus. Jenis tanda tangan yang didukung adalah Text, Image, Digital, Barcode, dan QR‑Code.

```python
def delete(self, signature_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_type | `SignatureType` | Jenis tanda tangan yang akan dihapus dari dokumen. |

**Returns:** DeleteResult: Contains lists of successfully deleted signatures and those that failed to delete.

| Melepaskan | Deskripsi |
| :- | :- |
| `Remarks` | - Pelajari lebih lanjut: - Lebih banyak tentang cara menghapus tanda tangan elektronik dari dokumen dalam C#: https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+type/ - Kasus penggunaan lanjutan untuk menghapus eSignature dokumen: https://docs.groupdocs.com/display/signaturenet/Deleting |

## delete {#signature_types}

Menghapus tanda tangan dari daftar `SignatureType` yang ditentukan dari dokumen.

Hanya tanda tangan yang ditambahkan oleh metode `Sign` dan ditandai sebagai tanda tangan ([`BaseSignature.is_signature`](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/)) yang akan dihapus. Jenis tanda tangan yang didukung adalah Text, Image, Digital, Barcode, dan QR‑Code.

Pelajari lebih lanjut
- More about how to delete electronic signature from document in C#: <https://docs.groupdocs.com/signature/net/delete+signatures+of+the+certain+types/>
- Advanced use cases of deleting document eSignatures: <https://docs.groupdocs.com/display/signaturenet/Deleting>

```python
def delete(self, signature_types):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_types | `List[SignatureType]` | Daftar jenis tanda tangan yang akan dihapus dari dokumen. |

**Returns:** `DeleteResult` with list of successfully deleted signatures and failed ones.

## delete {#signature_id}

Menghapus sebuah tanda tangan berdasarkan Id tanda tangan spesifiknya dari dokumen.

Pelajari lebih lanjut:

- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_id):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_id | `str` | Id tanda tangan yang akan dihapus dari dokumen. |

**Returns:** bool: True if the operation was successful.

## delete {#signature_ids}

Menghapus tanda tangan yang ditentukan dari dokumen.

Pelajari lebih lanjut:
- More about how to delete electronic signature from document in C#: https://docs.groupdocs.com/display/signaturenet/Delete+signatures+from+documents
- Advanced use cases of deleting document eSignatures: https://docs.groupdocs.com/display/signaturenet/Deleting

```python
def delete(self, signature_ids):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signature_ids | `List[str]` | Daftar pengidentifikasi tanda tangan yang akan dihapus dari dokumen. |

**Returns:** DeleteResult: `DeleteResult` with lists of successfully deleted signatures and failed ones.

### Contoh

```python
import shutil
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def delete_text_signature():
    # Kerjakan pada salinan karena delete() menyimpan perubahan ke dokumen yang dibuka.
    shutil.copy("signed.docx", "text_signature_deleted.docx")

    with Signature("text_signature_deleted.docx") as signature:
        options = TextSearchOptions()
        options.skip_external = True
        signatures = signature.search([options]).signatures
        if not signatures:
            return

        text_signature = signatures[0]
        result = signature.delete([text_signature.id])
        if result.successful:
            print(f"Deleted text signature '{text_signature.text}'")
        else:
            print(f"Failed to delete text signature '{text_signature.text}'")
```

### Lihat Juga
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
