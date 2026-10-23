---
title: "clone metode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menggandakan instance Tanda Tangan Metadata."
type: docs
url: /id/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Menggandakan instance Tanda Tangan Metadata.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Contoh

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Gandakan tanda tangan metadata standar dengan nilai baru
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Menggandakan instance tanda tangan metadata PDF dengan nilai yang diberikan.

```python
def clone(self, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | `Any` | Nilai untuk objek yang digandakan baru. |

**Returns:** A cloned metadata signature instance.

### Contoh

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Gandakan tanda tangan metadata yang ada dengan nilai baru
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Lihat Juga
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
