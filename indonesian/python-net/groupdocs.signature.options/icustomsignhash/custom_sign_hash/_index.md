---
title: "metode custom_sign_hash"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menandatangani hash yang diberikan menggunakan implementasi penandatanganan khusus."
type: docs
url: /id/python-net/groupdocs.signature.options/icustomsignhash/custom_sign_hash/
is_root: false
weight: 1010
---


## custom_sign_hash {#signable_hash-hash_algorithm-signature_context}

Menandatangani hash yang diberikan menggunakan implementasi penandatanganan khusus.

```python
def custom_sign_hash(self, signable_hash, hash_algorithm, signature_context):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signable_hash | `list[int]` | Nilai hash yang akan ditandatangani. |
| hash_algorithm | `HashAlgorithm` | Algoritma hash yang digunakan untuk menghasilkan hash. |
| signature_context | `SignatureContext` | Konteks yang menyediakan opsi tambahan terkait tanda tangan. |

**Returns:** bytes: The signed hash as bytes.

### Lihat Juga
* class [`ICustomSignHash`](/signature/python-net/groupdocs.signature.options/icustomsignhash/)
