---
title: "add_range Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Fügt eine Sammlung von Metadaten‑Unterschriften hinzu."
type: docs
url: /de/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

Fügt eine Sammlung von Metadaten‑Unterschriften hinzu.

```python
def add_range(self, signatures):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | Sammlung von Signaturen zum Hinzufügen. |

### Beispiel

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

### Siehe auch
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
