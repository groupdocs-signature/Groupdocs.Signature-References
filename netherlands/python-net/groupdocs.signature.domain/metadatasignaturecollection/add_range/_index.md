---
title: "add_range-methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Voegt een collectie metadata-handtekeningen toe."
type: docs
url: /nl/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

Voegt een collectie metadata-handtekeningen toe.

```python
def add_range(self, signatures):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Collectie van handtekeningen om toe te voegen. |

### Voorbeeld

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

### Zie ook
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
