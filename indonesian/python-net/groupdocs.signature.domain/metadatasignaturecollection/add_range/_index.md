---
title: "metode add_range"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menambahkan koleksi tanda tangan metadata."
type: docs
url: /id/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

Menambahkan koleksi tanda tangan metadata.

```python
def add_range(self, signatures):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Koleksi tanda tangan untuk ditambahkan. |

### Contoh

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

def sign_docx():
    with Signature("sample.docx") as signature:
        options = MetadataSignOptions()
        signatures = [
            WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
            WordProcessingMetadataSignature("DateCreated", datetime.now()),
            WordProcessingMetadataSignature("DocumentId", 123456),
            WordProcessingMetadataSignature("SignatureId", 123.456),
        ]
        options.signatures.add_range(signatures)
        result = signature.sign("signed.docx", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.name}")
```

### Lihat Juga
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
