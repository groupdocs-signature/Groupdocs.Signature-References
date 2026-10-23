---
title: "clone metode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengkloning sebuah instance Metadata Signature."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Mengkloning sebuah instance Metadata Signature.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Contoh

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Buat tanda tangan metadata baru berdasarkan tanda tangan AUTHOR yang telah ditentukan sebelumnya.
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Kloning instance Metadata Signature dengan nilai yang diberikan.

```python
def clone(self, value):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| value | `Any` | Nilai untuk objek kloning baru. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Contoh

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Gandakan tanda tangan metadata yang ada dengan nilai baru
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Lihat Juga
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
