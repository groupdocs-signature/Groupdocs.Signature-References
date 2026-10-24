---
title: "add_range yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "metadata signatures koleksiyonunu ekler."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

metadata signatures koleksiyonunu ekler.

```python
def add_range(self, signatures):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Eklenecek imzaların koleksiyonu. |

### Örnek

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

### Ayrıca Bakınız
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
